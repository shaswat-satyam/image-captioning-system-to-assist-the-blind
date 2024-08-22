# Image Captioning System to Assist The Blind

## Table of Contents

+ [About](#about)
+ [Getting Started](#getting_started)
+ [Screenshots](#outcomes)
    + [Dataset Split](#dataset_split)
    + [Model Anatomy](#model_anatomy)
    + [Project Workflow](#project_workflow)
    + [Results](#results)
    + [Final Outcome](#final_outcome)
    + [Additional Outputs](#additional_outputs)


## About <a name = "about"></a>

The goal of the project is to develop a system using deep learning techniques to assist visually impaired individuals in obtaining information by describing images taken by them. The system uses a CNN model and an NLP model to create a single image captioning system that takes image features as input and generates a text sequence describing the image. 

Incorporated state-of-the-art pre-trained models, such as ResNet50, VGG16, and VGG19, for image feature extraction and LSTM and Bidirectional LSTM for text generation. Evaluated various models to determine the best-performing model with a BLEU-score of 0.61 and deployed it using Flask and pyttsx3 for web and text-to-speech functionality in the app.

## Getting Started <a name = "getting_started"></a>

These instructions will get you a copy of the project up and running on your local machine.

1. Clone the project repository from GitHub:

```bash
git clone https://github.com/ammarlodhi255/image-captioning-system-to-assist-the-blind.git
```

2. Navigate to the project directory:

```bash
cd image-captioning-system-to-assist-the-blind
```

3. Create a virtual environment for the project:

```bash
python3 -m venv env
```

4. Activate the virtual environment:

```bash
source env/bin/activate
```

5. Install the required packages using pip:

```bash
pip install -r requirements.txt
```

6. Export the Flask app:

```bash
export FLASK_APP=app.py
```

7. Run the Flask app:

```bash
flask run
```

## Screenshots <a name = "screenshots"></a> 

### Dataset Split <a name = "dataset_split"></a> 
![Dataset Design](/screenshots/Dataset-design.png)

### Model Anatomy <a name = "model_anatomy"></a> 
![Model Anatomy](/screenshots/Model-Anatomy.png)

### Project Workflow <a name = "project_workflow"></a> 
![Project Workflow](/screenshots/Project-workflow.png)

### Results <a name = "results"></a> 
![Results Table](/screenshots/Results.png)

### Final Outcome <a name = "final_outcome"></a> 
![Home Interface](/screenshots/homeint.png)
![Browse](/screenshots/browse.png)
![Selected](/screenshots/selected.png)
![Choice](/screenshots/choice.png)
![Generating](/screenshots/generating.png)
![Generated](/screenshots/generated.png)

### Additional Outputs <a name = "additional_output"></a> 
![Output1](/screenshots/output1.png)
![Output2](/screenshots/output2.png)

