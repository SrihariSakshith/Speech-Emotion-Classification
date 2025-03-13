# Speech Emotion Classification for Crisis Intervention

## Introduction
This project focuses on classifying speech emotions to detect crisis situations that require immediate intervention. By analyzing audio files and predicting emotions such as **angry, happy, sad, neutral, and fear**, the system helps identify individuals who may need urgent assistance. This application is particularly useful for **mental health support, suicide prevention hotlines, and emergency response systems**.

## Dataset
The model is trained using multiple standard speech emotion datasets, including:
- **CREMA-D**
- **SAVEE**
- **RAVDESS**
- **TESS**

Each dataset contains labeled audio samples representing different emotions. The selected labels for classification include **angry, happy, sad, neutral, and fear**.

## Features & Model
- **Feature Extraction:** MFCC (Mel-Frequency Cepstral Coefficients) is used for processing audio files.
- **Model Architecture:** LSTM-based deep learning model is implemented.
- **Training Configuration:**
  - **Epochs:** 50
  - **Batch Size:** 32
  - **Optimizer:** Adam
  - **Loss Function:** Categorical Crossentropy
  - **Learning Rate:** 0.001

## Installation
To run this project, ensure you have the necessary dependencies installed. You can use Google Colab for execution.

### Required Libraries
```bash
pip install tensorflow librosa numpy pandas scikit-learn matplotlib
```

## Running the Project
1. **Upload the dataset files from Kaggle**
2. **Load the model and preprocess audio samples**
3. **Run the classification script in Google Colab**
4. **Interpret results based on predicted emotions**

## Results & Performance
- The model achieved an **accuracy of approximately 53%** on test data.
- It performs well in classifying **angry and surprise** emotions but needs improvements for other categories.
- Further enhancements can be made using **data augmentation and additional feature extraction techniques**.

## Application & Use Cases
- **Mental health monitoring**
- **Emergency response for crisis situations**
- **Call center emotion analysis**
- **Human-computer interaction improvements**

## Future Enhancements
- Implement **real-time speech recognition** for faster emotion detection.
- Integrate **more robust deep learning models** to improve accuracy.
- Expand the dataset for better generalization across diverse speech patterns.

## Contributors
- **Kotichintala Srihari Sakshith (kotichintalasriharisakshith@gmail.com, Vasavi College of Engineering)**
- **Cholleti Pranav (pranavcholleti@gmail.com, Vasavi College of Engineering)**
- **Omkar (omkarkoty2004@gmail.com, Vasavi College of Engineering)**
