# TrashNet Classifier

A deep learning application for automated waste classification using computer vision. This project leverages pre-trained models to classify images of waste into different categories, helping to automate waste sorting and improve recycling efficiency.

## Overview

TrashNet Classifier is a web-based application that uses deep learning to identify and classify different types of waste materials. The system is designed to assist in waste management by automatically categorizing trash images into their respective classes.

## Waste Categories

The classifier typically identifies the following waste categories:
- **Cardboard** - Cardboard boxes and packaging materials
- **Glass** - Glass bottles, jars, and containers
- **Metal** - Metal cans, containers, and aluminum products
- **Paper** - Paper products, newspapers, and documents
- **Plastic** - Plastic bottles, containers, and packaging
- **Trash** - General waste and non-recyclable materials

## Features

- Real-time image classification
- Web-based user interface
- Pre-trained model support
- High accuracy classification
- Easy-to-use upload interface
- Instant prediction results

## Technology Stack

- **Python** - Core programming language
- **Deep Learning Framework** - TensorFlow/Keras
- **Web Framework** - Streamlit for web interface
- **Computer Vision** - Image preprocessing and augmentation
- **Model Architecture** - CNN-based classification models

## Prerequisites

- Python 3.7 or higher
- pip package manager
- Virtual environment (recommended)

## Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/AhmedMohamedKame1/trashnet-classifier.git
   cd trashnet-classifier
   ```

2. **Create a virtual environment** (recommended)
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

## Project Structure

```
trashnet-classifier/
├── app.py                          # Main application file
├── requirements.txt                # Project dependencies
├── .python-version                 # Python version specification
└── saved_models/
    └── trashnet_models/           # Trained model files
```

## 🎮 Usage

1. **Start the application**
   ```bash
   python app.py
   ```

2. **Classify waste images**
   - Upload an image of waste material
   - Click the classify/predict button
   - View the classification results and confidence scores

## Model Information

The classifier uses pre-trained deep learning models stored in the `saved_models/trashnet_models/` directory. These models have been trained on the TrashNet dataset, which contains thousands of images across different waste categories.

## Dataset

This project is based on the TrashNet dataset, which consists of images of waste items photographed on a white posterboard with natural and room lighting. The original dataset can be found in various repositories and typically includes:
- Over 1,9000 images
- 6 waste categories
- Images resized to standard dimensions
- High-quality photographs for accurate classification

## Model Performance

The classifier aims to provide:
- High accuracy across all waste categories
- Fast inference time for real-time classification
- Robust performance on various image qualities
- Reliable predictions for practical applications
