# Emotion Detection Using Machine Learning  

## Overview  
This project focuses on emotion detection by classifying user comments into different emotional categories using machine learning techniques. The model is trained on a Kaggle dataset containing labeled text data and achieves high accuracy in predicting emotions.  

## Features  
- Text preprocessing (stop-word removal, lowercasing, special character removal).  
- Feature extraction using TF-IDF and Bag of Words.  
- Classification using Logistic Regression and Random Forest.  
- Achieves 90% accuracy on the test dataset.  

## Dataset  
The dataset consists of two columns:  
- **Text**: User comments.  
- **Label**: Numeric values (0–5) representing emotions such as Sad, Happy, Angry, etc.  

## Preprocessing Steps  
- Removing stop words.  
- Converting text to lowercase.  
- Removing special characters and punctuation.  

## Model Training  
The following machine learning models were implemented:  
- **Logistic Regression**: A statistical model for classification.  
- **Random Forest**: An ensemble learning technique that improves accuracy.  

## Performance  
- The model achieved **90% accuracy** on the test dataset.  

## Future Enhancements  
- Implementing deep learning models like LSTMs.  
- Using a larger, real-world dataset for better generalization.  

## Installation & Usage  
### Requirements  
- Python 3.x  
- NumPy  
- Pandas  
- Scikit-learn  
- Matplotlib  

### Steps to Run  
1. Clone the repository:  
   ```bash
   git clone https://github.com/your-username/emotion-detection.git
   cd emotion-detection
