# 🎙️ Speech Emotion Recognition (SER)

This project detects emotions from speech using the RAVDESS dataset and a Multi-Layer Perceptron (MLP) classifier.

## 📌 Key Features
- **Dataset**: RAVDESS (8 emotions: neutral, calm, happy, sad, angry, fearful, disgust, surprised)  
- **Feature Extraction**: MFCC, Chroma, Mel spectrogram  
- **Data Augmentation**: Gaussian noise, pitch shift, time stretch (via `audiomentations`)  
- **Model**: MLPClassifier with hyperparameter tuning using `RandomizedSearchCV`  
- **Evaluation**: Accuracy, classification report, confusion matrix  

## 📦 Tech Stack
Python, Librosa, Scikit-learn, Audiomentations, Matplotlib, Seaborn

## 📁 Output
- `ser_mlp_model.pkl`: Trained model  
- `label_encoder.pkl`: Label encoder  
- `data_path.csv`: File-emotion mapping  

## 🚀 How to Run
1. Upload and unzip the dataset  
2. Run feature extraction and training  
3. Evaluate model and export files  

