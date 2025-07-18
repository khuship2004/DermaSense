

# DermaSense

**AI-Powered Facial Skincare Recommendation System**

---

## Overview

DermaSense is a web application that leverages deep learning and classical machine learning to provide personalized skincare and makeup recommendations based on user facial images and features. The system analyzes skin type, acne severity, and skin tone using multiple ML models, delivering tailored product suggestions for optimal skincare routines.

---

## Features

- **Skin Type & Acne Detection:**  
  Utilizes Keras/TensorFlow CNNs to classify skin type (dry, normal, oily) and acne severity (low, moderate, severe) from user-uploaded facial images.

- **Skin Tone Analysis:**  
  Employs a custom K-Nearest Neighbors (KNN) model for robust skin tone detection, enhancing the personalization of recommendations.

- **Personalized Recommendations:**  
  Combines ML predictions with user input to suggest skincare and makeup products best suited to individual needs.

- **Modern Web Interface:**  
  React.js frontend for seamless image upload, user interaction, and real-time results.

---

## Machine Learning Stack

- **Skin Type Model:**  
  CNN (EfficientNet B0, transfer learning) for skin type classification.

- **Acne Severity Model:**  
  CNN (EfficientNet B0) for acne severity assessment.

- **Skin Tone Model:**  
  KNN-based classifier for skin tone detection.

- **Recommendation Engine:**  
  Content-based filtering and cosine similarity for product matching.

---

## How to Run

1. **Clone the repository** and create a Python virtual environment:
    ```bash
    pip install -r requirements.txt
    ```

2. **Start the backend (Flask API):**
    ```bash
    cd backend
    python app.py
    ```

3. **Start the frontend (React app):**
    ```bash
    cd frontend
    npm install
    npm start
    ```

4. **Usage:**  
   Access the app in your browser, upload a facial image, and receive instant, AI-powered skincare recommendations.

---

## Tech Stack

- **Backend:** Python, Flask, TensorFlow, Keras, Scikit-learn
- **Frontend:** React.js, Material-UI
- **ML Models:** EfficientNet B0 (CNN), KNN

---
