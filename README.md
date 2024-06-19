# DermAI: Automated Skin Disease Prediction and Report Generation

## Overview

DermAI is an AI-powered application designed to predict skin diseases from images using deep learning models. It generates detailed diagnosis reports and sends them directly to patients via email.

## Features

- **Automated Diagnosis:** Predicts skin diseases from input images.
- **Report Generation:** Generates detailed diagnosis reports in DOCX format.
- **Email Integration:** Sends diagnosis reports directly to patients via email.

## System Requirements

- Python 3.6+
- TensorFlow/Keras
- NumPy
- Matplotlib
- Pillow
- Docx
- smtplib

## Installation and Setup

1. Clone the repository
2. Install dependencies
3. Train a .h5 model using any alg. (Resnet50 was used for the training of my model)
4. Download the trained model (`my_model.h5`) and place it in the project directory.
5. Install Ollama and donwload llama2 llm for generating the report.
6. Obtain a Gmail App Password for email functionality.
   
## Usage

1. Run the script:
2. Enter the path to the image, patient name, and patient email when prompted.
3. The application will predict the skin disease, generate a report, and email it to the patient.

## Future Enhancements

- **Enhanced Disease Descriptions:** Provide more detailed descriptions and treatment suggestions based on predicted diseases.
- **User Interface:** Develop a user-friendly interface for easy image upload and interaction.
- **Multi-language Support:** Extend language capabilities for broader accessibility.

### References

- Keras Documentation: [https://keras.io](https://keras.io)
- Python Imaging Library (Pillow): [https://pillow.readthedocs.io](https://pillow.readthedocs.io)
- Matplotlib Documentation: [https://matplotlib.org](https://matplotlib.org)
- Python-docx Documentation: [https://python-docx.readthedocs.io](https://python-docx.readthedocs.io)
