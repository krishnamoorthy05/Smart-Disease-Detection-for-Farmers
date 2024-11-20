*Bean Crop Disease Detection with Transfer Learning

This project leverages TensorFlow and MobileNet to build a machine learning model for classifying bean crop diseases through image analysis, assisting farmers in identifying infected plants. By applying transfer learning, the initiative ensures efficient training on the TensorFlow Beans dataset and deploys a user-friendly Streamlit application for practical usage.

*📖 Project Overview

The goal is to create an accessible solution for detecting diseases in bean crops, enabling farmers to identify infections efficiently. By using a pre-trained MobileNet model, the project classifies bean images into distinct categories for accurate disease identification.

*🚀 Key Components

*1. Dataset Loading
Load the TensorFlow Beans dataset using TensorFlow Datasets (TFDS).
Display dataset structure and class labels for better understanding of the data distribution.
2. Data Visualization
Visualize sample images with class labels to analyze dataset diversity and potential classification challenges.
3. Data Preprocessing
Resize images to 224x224 pixels to match MobileNet's input requirements.
Normalize pixel values to a range of 0 to 1 for improved model performance.
4. Model Setup for Transfer Learning
Utilize pre-trained MobileNet weights from ImageNet.
Freeze early layers for general feature extraction and fine-tune later layers for bean disease classification.
5. Training the Model
Train the model on preprocessed data using early stopping to prevent overfitting.
Optimize key hyperparameters like batch size, learning rate, and epochs for best performance.
6. Model Evaluation
Evaluate performance on a test dataset using metrics like accuracy, precision, and recall.
Analyze results to identify strengths, weaknesses, and areas for improvement.
7. Model Saving and Reusability
Save the trained model in .keras format for future use.
Provide guidelines for loading and reusing the model in other environments.
8. Streamlit Application Deployment
Build a simple Streamlit app for farmers to upload bean images and receive disease predictions.
Display class labels with confidence scores and handle errors gracefully for unsupported file types.
🌟 Conclusion

This project bridges technology and agriculture, offering an innovative tool for disease detection in bean crops. By combining transfer learning with a user-friendly application, it enhances crop management practices, boosting agricultural productivity.
