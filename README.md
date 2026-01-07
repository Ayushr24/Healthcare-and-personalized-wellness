# HealthClassification

HealthClassification is an AI-based health and lifestyle prediction system that classifies an individual’s health status based on daily activity and physiological indicators. The project combines deep learning–based classification with an NLP-powered chatbot to provide contextual health insights.

## Project Overview
The system predicts health status using structured inputs such as Daily Steps, BMI, Profession, Stress Level, Sleep Duration, and related lifestyle parameters. In addition, an AI assistant is integrated to address health-related queries and recommend appropriate medical consultation when required.

## Components

### Deep Learning Module
The `DL` directory contains the complete training and evaluation pipeline for the health classification model, including:
- Data preprocessing and feature handling
- Model architecture design
- Training, validation, and performance evaluation

### NLP / Chatbot Module
The `Health_T5` module implements a **T5-small** model fine-tuned to function as a health-focused chatbot.  
It assists users by:
- Answering basic medical and lifestyle queries
- Providing insights into possible causes
- Suggesting the type of medical specialist to consult

### Web Application
The repository also includes JSON, HTML, CSS, and Python files that together form an end-to-end web-based application.  
This interface integrates the deep learning model and the NLP assistant into a single user-facing platform.

## My Contribution
- Designed and implemented the core deep learning classification model  
- Built the training and evaluation pipeline  
- Integrated the NLP chatbot with the prediction system  
- Led system-level integration and testing  

## Collaboration & Credits
This project was developed as a team collaboration.  
My work focused on model development, system integration, and experimentation within the overall project.

Original collaboration repository:  
https://github.com/<partner-username>/<original-repo-name>

## Disclaimer
This project is for educational and research purposes only.  
The code should be modified and validated before any real-world or clinical use.
