# Cotton Plant Disease Detection System


An AI-powered web-based system for automated cotton leaf disease detection using the EfficientNetV2 Deep Learning model. The system analyzes cotton leaf images and predicts whether the plant is healthy or affected by a disease, helping farmers and agricultural experts identify diseases at an early stage.

---

## Project Overview

Cotton is one of the most important cash crops worldwide. Diseases affecting cotton plants can significantly reduce crop yield and quality. Traditional disease diagnosis requires expert knowledge and manual inspection, which can be time-consuming and costly.

This project uses Deep Learning and Computer Vision techniques to automatically detect diseases from cotton leaf images. The trained EfficientNetV2 Convolutional Neural Network (CNN) model extracts visual features from leaf images and classifies them into disease categories.

The system is deployed as a web application using Flask, allowing users to upload leaf images and receive instant disease predictions.

---

## Objectives

The main objectives of this project are:

- Detect cotton plant diseases automatically.
- Reduce dependency on manual disease inspection.
- Improve disease diagnosis speed and accuracy.
- Assist farmers in taking timely preventive measures.
- Deploy an easy-to-use web-based prediction system.

---

## Key Features

### Deep Learning Features

- Image Classification using EfficientNetV2
- Transfer Learning Implementation
- Automated Feature Extraction
- Disease Category Prediction
- Image Preprocessing Pipeline
- Model Evaluation and Validation

### Web Application Features

- Image Upload Interface
- Instant Disease Prediction
- User-Friendly Dashboard
- Flask-Based Deployment
- Responsive Design

---

## Machine Learning Model

### Model Used

**EfficientNetV2**

EfficientNetV2 is a state-of-the-art Convolutional Neural Network architecture designed for faster training and higher accuracy while maintaining computational efficiency.

### Why EfficientNetV2?

- Faster Training
- Better Accuracy
- Lower Computational Cost
- Optimized Feature Extraction
- Suitable for Agricultural Disease Detection

---

## Technologies Used

## Programming Language

- Python

## Deep Learning Framework

- TensorFlow
- Keras

## Machine Learning

- EfficientNetV2
- Transfer Learning

## Data Processing

- NumPy
- Pandas
- OpenCV

## Visualization

- Matplotlib
- Seaborn

## Web Development

- Flask
- HTML5
- CSS3
- JavaScript

## Development Tools

- Google Colab
- VS Code
- Git
- GitHub

---

## Project Structure

```text
Cotton-Disease-Detection-System/
│
├── app.py
├── model.py
├── train_model.ipynb
├── efficientnetv2_model.h5
│
├── static/
│   ├── css/
│   ├── images/
│
├── templates/
│   ├── index.html
│   ├── result.html
│
├── dataset/
│   ├── Healthy/
│   ├── Diseased/
│
├── README.md
└── requirements.txt
```

---

## System Workflow

```text
Cotton Leaf Image
        ↓
Image Upload
        ↓
Image Preprocessing
        ↓
EfficientNetV2 Model
        ↓
Feature Extraction
        ↓
Disease Classification
        ↓
Prediction Result
```

---

## Dataset Preparation

The dataset consists of cotton leaf images categorized into different classes.

### Data Processing Steps

- Image Collection
- Image Labeling
- Image Resizing
- Normalization
- Data Augmentation
- Train/Test Split

### Data Augmentation Techniques

- Rotation
- Horizontal Flip
- Vertical Flip
- Zoom
- Brightness Adjustment

These techniques improve model generalization and reduce overfitting.

---

## Model Training

The model training process includes:

### Step 1

Load and preprocess images.

### Step 2

Apply data augmentation.

### Step 3

Load pre-trained EfficientNetV2 weights.

### Step 4

Freeze initial layers.

### Step 5

Train classification layers.

### Step 6

Fine-tune deeper layers.

### Step 7

Evaluate model performance.

### Step 8

Save best-performing model.

---

## Evaluation Metrics

The model performance is evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

---

Installation Guide

## Clone Repository

```bash
git clone https://github.com/mohsinalipydev/Cotton-Disease-Detection-System.git
```

Move to project folder:

```bash
cd Cotton-Disease-Detection-System
```

---

## Create Virtual Environment

Windows:

```bash
python -m venv venv
venv\Scripts\activate
```

Linux/Mac:

```bash
python3 -m venv venv
source venv/bin/activate
```

---

## Install Dependencies

```bash
pip install -r requirements.txt
```

---

## Run Application

Deployment

The application was deployed using Flask and Ngrok to provide public access to the locally hosted web application.

### Deployment Workflow

```text
User
  ↓
Ngrok Public URL
  ↓
Flask Web Server
  ↓
EfficientNetV2 Model
  ↓
Disease Prediction
```

### Running with Flask

```bash
python app.py
```

### Exposing Flask App with Ngrok

Install ngrok:

```bash
pip install pyngrok
```

Authenticate ngrok:

```bash
ngrok config add-authtoken YOUR_NGROK_TOKEN
```

Create a public tunnel:

```bash
ngrok http 5000
```

Ngrok generates a public URL that can be used to access the application from any device connected to the internet.

---

## System Architecture

```text
Cotton Leaf Image
        ↓
Flask Web Interface
        ↓
Image Preprocessing
        ↓
EfficientNetV2 CNN Model
        ↓
Disease Classification
        ↓
Prediction Result
        ↓
Displayed to User
```

## Application Usage

1. Open the web application.
2. Upload a cotton leaf image.
3. Click Predict.
4. Wait for the model prediction.
5. View disease classification result.

---

## Real-World Applications

- Smart Agriculture
- Precision Farming
- Crop Monitoring
- Disease Surveillance
- Agricultural Research
- Farmer Decision Support Systems

---

## Future Enhancements

- Mobile Application Integration
- Real-Time Camera Detection
- Disease Severity Analysis
- Fertilizer Recommendations
- Treatment Suggestions
- Multi-Crop Disease Detection
- Cloud Deployment

---

## Future Scope

The project can be extended into a complete Agricultural AI Platform featuring:

- IoT Sensor Integration
- Drone-Based Monitoring
- Weather-Based Disease Forecasting
- Yield Prediction
- AI Chatbot for Farmers

---


## Author

**Mohsin Ali**

Machine Learning Enthusiast | Deep Learning Developer | AI Research Learner

---

## License

This project is developed for academic and research purposes.

Feel free to use, modify, and extend the project for educational purposes.
