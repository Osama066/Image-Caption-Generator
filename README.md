# Image-Caption-Generator
# Image Caption Generator

This repository contains a Streamlit application that generates captions for images using a pre-trained VisionEncoderDecoderModel from the Hugging Face Transformers library.

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Setup](#setup)
- [Usage](#usage)

## Overview
The Image Caption Generator uses the `nlpconnect/vit-gpt2-image-captioning` model to generate captions for images. The model combines a Vision Transformer (ViT) for image feature extraction and GPT-2 for text generation. This application provides a user-friendly interface to upload an image and generate a caption for it.

## Features
- Upload an image file in JPG, JPEG, or PNG format.
- Generate a caption for the uploaded image.
- Display the uploaded image and the generated caption.

## Setup
To run this application locally, follow these steps:

1. **Clone the repository**:
    ```bash
    git clone https://github.com/your-username/image-caption-generator.git
    cd image-caption-generator
    ```

2. **Create a virtual environment**:
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3. **Install the required packages**:
    ```bash
    pip install -r requirements.txt
    ```

4. **Run the Streamlit app**:
    ```bash
    streamlit run ap.py
    ```

## Usage
1. Open the application in your browser. It will be running at `http://localhost:8501`.
2. Upload an image by clicking on the "Choose an image..." button.
3. Click the "Generate Caption" button to generate and display the caption for the uploaded image.


![Screenshot 2024-04-25 193300](https://github.com/Osama066/Image-Caption-Generator/assets/109853647/ed420f22-d80a-4661-91ec-a1cff36a29be)

