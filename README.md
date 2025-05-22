# Leaf Disease Detection Using Aerial Images

This project demonstrates a deep learning pipeline developed to identify and classify plant diseases from aerial leaf imagery. Leveraging a custom convolutional neural network (CNN), the system accurately detects 38 types of crop diseases from over 87,000 high-resolution images, supporting precision agriculture with scalable AI-driven diagnostics.
Employed data preprocessing, feature extraction, and model training with categorical cross-entropy loss and Adam optimizer. Achieved model accuracy through validation and fine-tuning hyperparameters

## Project Highlights

- Dataset: 87,000+ aerial crop leaf images  
- Categories: 38 distinct plant diseases  
- Model: Custom CNN using TensorFlow & Keras  
- Performance:
  - Training Accuracy: 97.82%
  - Validation Accuracy: 94.59%
  - Test Accuracy: 95%
  - F1-Score: 0.95

## Repository Contents

- `Train_plant_disease_.ipynb` – Model training, preprocessing, and evaluation
- `Test_plant_disease_.ipynb` – Inference and result visualization

## Sample Visuals

## Input Leaf Image
![Input Leaf Image](./Input%20Leaf%20Image.jpg)

## Predicted Disease
![Predicted Disease](./Predicted%20Disease.jpg)

**Training vs Validation Accuracy:**  
![Accuracy Plot](./5f1dc9f0-a355-4493-9650-0e6662d57411.png)

**Confusion Matrix:**  
![Confusion Matrix](./e6d6660a-6af9-4782-9378-2c6edda16872.png)

## Tech Stack

- Languages: Python  
- Libraries: TensorFlow, Keras, OpenCV, NumPy, Matplotlib, Pandas  
- Tools: Jupyter Notebook, Google Colab  

## Installation

```bash
git clone https://github.com/JomainaAhmed/Leaf-Disease-Detection-using-Aerial-Images.git
cd Leaf-Disease-Detection-using-Aerial-Images
pip install -r requirements.txt

