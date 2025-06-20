# Brain-tumor-detection
Brain MRI classifier using deep learning, integrated into a Telegram bot.

# Brain Tumor MRI Detection Telegram Bot

This project implements a deep learning-based Telegram bot that classifies brain MRI scans into four categories:

- Glioma
- Meningioma
- Pituitary
- No Tumor

The classification is powered by a convolutional neural network (CNN) built using TensorFlow and Keras, trained on a labeled dataset of brain MRI images.

## Features

- Accepts MRI images via Telegram
- Preprocesses and classifies using a trained CNN model
- Responds with tumor type and confidence score

## Dataset

The model is trained on the [Brain Tumor MRI Dataset by Masoud Nickparvar](https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset), which contains T1-weighted contrast-enhanced images of brain tumors and healthy scans.


## Instructions

1. Clone this repository
2. Upload your trained model file (`brain_tumor_model.h5`) into the `model/` directory
3. Edit `bot.py` to include your Telegram bot token
4. Install dependencies:


## Dependencies

- TensorFlow
- NumPy
- OpenCV
- python-telegram-bot
- nest_asyncio

These are included in `requirements.txt`.

## Example Bot Interaction

User sends an MRI scan → Bot replies with:

Prediction: Glioma
Confidence: 91.7%




