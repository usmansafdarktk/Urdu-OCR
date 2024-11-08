# Urdu OCR
This repository provides resources for generating Urdu words, capturing images, and applying deep learning models for Optical Character Recognition (OCR).

## Project Overview

The Urdu OCR project aims to develop a robust system for recognizing Urdu characters using deep learning techniques. Key components include:

- **Dataset Creation**: Generating a diverse set of Urdu words and their corresponding images.
- **Model Training**: Applying advanced deep learning architectures to enhance character recognition accuracy.

## Word Generation

- **Purpose**: Generate a comprehensive dataset of Urdu words for training OCR models.
- **Methodology**:
  - Utilizes defined sets of characters (start, middle, end) to create words of varying lengths (1 to 5 characters).
  - Saves generated words and corresponding labels in a CSV format for easy access and processing.

## Image Generation

- **Purpose**: Create visual representations of the generated Urdu words to be used in model training.
- **Methodology**:
  - Formats each generated word in a Microsoft Word document.
  - Captures screenshots of the words to produce images, ensuring a diverse dataset.
  - Images are saved in a structured directory for subsequent processing.


## Preview
The following are two examples of images generated:

![Screenshot 2024-10-27 143322](https://github.com/user-attachments/assets/bf89e89a-8e0e-4f04-801f-bd73114fb2b4)

<br>

![Screenshot 2024-10-27 143414](https://github.com/user-attachments/assets/c30e191f-a0b2-4e63-8b92-385a0f91c487)


## Deep Learning Models

This project implements the following models for OCR tasks:

- **Hybrid CNN+LSTM**:
  - Combines Convolutional Neural Networks (CNNs) for feature extraction with Long Short-Term Memory (LSTM) networks for sequence prediction.
  - Optimized for recognizing sequential data in character recognition.

- **VGG16**:
  - A deep convolutional neural network known for its simplicity and depth.
  - Utilized for its strong performance in image classification tasks, adapted for Urdu character recognition.

- **Deep CNN**:
  - A custom-designed deep convolutional neural network.
  - Tailored architecture to enhance the recognition of complex Urdu characters.

## Getting Started

To set up the Urdu OCR project locally, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/Urdu-OCR.git
   cd Urdu-OCR

2. Install the required packages and run the scripts.