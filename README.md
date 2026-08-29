# Deep-Learning-Based-Plant-Disease-Classification-with-Explainable-AI

An AI-powered plant disease detection system that uses **deep learning and Explainable AI (XAI)** to classify plant diseases from leaf images and provide interpretable explanations for model predictions using **LIME and SHAP**.

## 📌 Overview

Plant diseases can significantly affect crop productivity and agricultural sustainability. Early and accurate disease identification can help farmers take timely action and reduce crop losses.

This project develops an image-based deep learning system for **automated plant disease classification**. A CNN-based model with transfer learning is trained on plant leaf images, while **LIME and SHAP** are used to explain which regions of an image contributed to the model's prediction.

The application provides an interactive **Streamlit web interface** where users can upload a leaf image, obtain a predicted disease class, view the model's confidence, and explore visual explanations.

## ✨ Features

* 🌿 Automated plant disease classification from leaf images
* 🧠 Deep learning with CNNs and transfer learning
* 🖼️ Image preprocessing and augmentation
* 🔍 Explainable AI using **LIME**
* 📊 Model interpretation using **SHAP**
* 🎯 Prediction confidence scores
* 🌐 Interactive Streamlit web application
* 🌱 Support for multiple plant disease classes

## 🧠 Model Architecture

The project uses a **Convolutional Neural Network (CNN)** with transfer learning from a pre-trained deep learning model.

Transfer learning allows the model to leverage visual features learned from large-scale image datasets and adapt them to plant disease classification.

## 📂 Project Structure

```text
Plant-Disease-Detection/
│
├── data/
│   └── # Plant disease image dataset
│
├── models/
│   └── best_model.h5
│
├── utils/
│   └── # Helper functions
│
├── app.py
│   └── # Streamlit application
│
├── train.py
│   └── # Model training and XAI functions
│
├── requirements.txt
│   └── # Python dependencies
│
└── README.md


## 🔮 Future Improvements

* Add more plant species and disease classes.
* Improve classification performance using advanced architectures.
* Compare multiple transfer-learning models.
* Add model performance metrics such as precision, recall, F1-score, and confusion matrix.
* Improve SHAP visualization for image-based predictions.
* Deploy the application using Streamlit Cloud or another cloud platform.
* Develop a mobile-friendly interface.
* Add disease treatment and prevention recommendations.

📜 License

This project is licensed under the MIT License
