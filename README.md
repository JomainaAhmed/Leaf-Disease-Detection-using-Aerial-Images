# 🌿 Leaf-Disease-Detection-using-Aerial-Images 
This project demonstrates a deep learning pipeline developed to identify and classify plant diseases from aerial leaf imagery. Leveraging a custom convolutional neural network (CNN), the system accurately detects 38 types of crop diseases from over 87,000 high-resolution images, supporting precision agriculture with scalable AI-driven diagnostics.
Employed data preprocessing, feature extraction, and model training with categorical cross-entropy loss and Adam optimizer. Achieved model accuracy through validation and fine-tuning hyperparameters

Project Summary:
Model Type: Custom CNN
Frameworks: TensorFlow, Keras
Dataset: 87,000+ aerial images of crop leaves

Performance:
Training Accuracy: 97.82%
Validation Accuracy: 94.59%
Test Accuracy: 95%
F1-Score: 0.95

Repository Contents:
Train_plant_disease_.ipynb – Contains the training pipeline, data preprocessing, augmentation, model building, training, and evaluation.
Test_plant_disease_.ipynb – Script for loading the trained model and running inference on new images.

Key Features:
Lightweight yet deep CNN designed for efficient aerial image classification.
Utilizes advanced training strategies: Adam optimizer, learning rate scheduling, early stopping, and model checkpointing.
GPU acceleration enabled for faster training.
Strong generalization and performance across diverse plant disease categories.

Technologies Used:
Languages: Python
Libraries: TensorFlow, Keras, OpenCV, NumPy, Matplotlib, Pandas
Tools: Jupyter Notebook, Google Colab
Other Skills: Image processing, model evaluation, performance visualization

Setup Instructions
1. Clone this repository:
git clone https://github.com/JomainaAhmed/Leaf-Disease-Detection-using-Aerial-Images.git
cd Leaf-Disease-Detection-using-Aerial-Images

2. Install the dependencies:
pip install -r requirements.txt

3. Launch the notebooks:
jupyter notebook

4. Execute in order:
Train_plant_disease_.ipynb
Test_plant_disease_.ipynb

Future Enhancements
Integration with drones or mobile devices for real-time detection.
Improve robustness using transfer learning or ensemble models.

👩‍💻 About Me
Jomaina Hafiz Ahmed
B.Tech in Computer Science & Engineering
📍 Punjab, India
📫 jomaina.ahmed@gmail.com
🔗 LinkedIn | GitHub
