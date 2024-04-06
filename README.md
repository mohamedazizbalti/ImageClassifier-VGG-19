# DataQuest Hackathon - Multi-Class Image Classification

## Introduction
Welcome to the repository for the DataQuest Hackathon - Multi-Class Image Classification challenge! This repository contains the code for building a deep learning model to classify images into multiple classes. The challenge is part of the DataQuest hackathon scheduled for the 24th and 25th of February.

## Problem Description
The challenge focuses on multi-class image classification using a simple dataset. Participants are required to build a deep learning model that accurately classifies images into one of several predefined classes. The evaluation metric for this challenge is accuracy, where higher accuracy leads to a higher rank in the competition.

## Approach
We use a pre-trained EfficientNetB0 model as the base architecture and add a few additional layers on top to fine-tune it for our specific task. The model is compiled with the Adam optimizer and trained using sparse categorical cross-entropy loss.

## Repository Structure
- `model.ipynb`: Jupyter Notebook containing the code for model training and evaluation.
- `data/`: Directory containing the dataset for training and testing the model.
- `requirements.txt`: List of Python dependencies required to run the code.

## Instructions
1. Clone the repository to your local machine.
2. Install the required dependencies by running `pip install -r requirements.txt`.
3. Open and run the `model.ipynb` notebook to train and evaluate the model.
4. Modify the code as needed to experiment with different architectures, hyperparameters, or preprocessing techniques.

## Dataset
The dataset for this challenge is provided within the `data/` directory. It contains labeled images for training and testing the model.

## Results
After training the model, the final accuracy and performance metrics will be reported in the notebook.

## Contact
For any questions or clarifications regarding the challenge or the code, feel free to contact [Mohamed Aziz Balti](https://github.com/mohamedazizbalti).
