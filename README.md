# EEG_Emotion_recognition

This Colab notebook demonstrates how to perform emotion detection using deep learning techniques. It utilizes a dataset containing various features and corresponding emotion labels to train a deep learning model for emotion classification.

# Notebook Features

Data Loading: The notebook begins by loading the dataset from a CSV file named "emotions.csv."

Data Exploration: It explores the dataset by displaying the first few rows, checking the column names, and inspecting class distribution.

Data Preprocessing: The dataset is preprocessed by scaling the features using StandardScaler and encoding the emotion labels.

Model Building: A deep learning model is constructed using TensorFlow/Keras. It includes LSTM layers for sequence data and is compiled with the categorical cross-entropy loss function.

Training: The model is trained on the preprocessed data with 50 epochs, and the training history is stored for evaluation.

Evaluation: The model's performance is evaluated using the test data, and the test accuracy is calculated.

# Usage
Open the Colab notebook using the "Open In Colab" button at the top of this README.

Follow the steps in the notebook to load, preprocess, build, train, and evaluate the emotion detection model.

Observe the test accuracy to assess the model's performance.

Feel free to modify the notebook or use it as a starting point for your own emotion detection projects.

# Dataset
The dataset used in this notebook is loaded from a CSV file named "emotions.csv." It contains various features and emotion labels for classification. Data used here is from kaggle.

# Dependencies

The notebook uses the following Python libraries:

NumPy

pandas

Seaborn

TensorFlow/Keras

Matplotlib

These dependencies are pre-installed in Google Colab, so you don't need to install them separately.





