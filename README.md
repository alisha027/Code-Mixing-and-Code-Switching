# Code-Mixing and Code-Switching Detection

## 📌 Project Overview
This project focuses on detecting **code-mixing and code-switching** in multilingual text using **Natural Language Processing (NLP) techniques**. It utilizes **language detection, n-gram analysis, and machine learning classifiers** to identify mixed-language usage within a dataset.

## ⚡ Features
- **Preprocessing:** Tokenization, stopword removal, and lemmatization  
- **Language Detection:** Identifies languages at the token level  
- **N-gram Analysis:** Generates bigrams for pattern recognition  
- **Machine Learning Models:** Uses **SVM, Logistic Regression, CNN, and LSTM** for classification  
- **Visualization:** Plots training/validation accuracy and loss curves  

## 🛠️ Technologies Used
- **Languages:** Python  
- **Libraries:** NLTK, Scikit-learn, TensorFlow, Pandas, NumPy, Matplotlib, Seaborn  
- **Machine Learning Models:** SVM, Logistic Regression, CNN, LSTM  

## 📂 Project Structure
├── data/ # Dataset files ├── src/ # Source code files │ ├── preprocessing.py # Text preprocessing functions │ ├── language_detection.py # Language identification methods │ ├── modeling.py # ML models for classification │ ├── visualization.py # Plot training metrics │ └── main.py # Main execution script ├── requirements.txt # List of dependencies ├── README.md # Project documentation └── final_code_mix_code_switch.py # Full implementation script
📊 Results
SVM Model Accuracy: 94%

CNN & LSTM Performance: Achieved high accuracy with significant improvements in text classification
