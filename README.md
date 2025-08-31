# Enhancing Language Representation with Emotional Intelligence: A Weighted TF-IDF Approach

## Overview
This project explores a novel approach to text representation by integrating emotional intelligence into the TF-IDF algorithm. Traditional TF-IDF focuses on word frequency and importance but often ignores emotional dimensions of language. By applying a weighted TF-IDF model, this project enhances sentiment-aware language representation and improves classification performance in sentiment analysis tasks. The work also compares the performance of Convolutional Neural Networks (CNNs) and Recurrent Neural Networks (RNNs), highlighting how RNNs capture long-term dependencies for richer context understanding.

## Features
- Weighted TF-IDF Representation – incorporates emotional weights into classical TF-IDF for improved text analysis.  
- Sentiment Analysis – classifies text into positive, negative, or neutral sentiment.  
- Deep Learning Models – implementation of CNN and RNN for NLP tasks.  
- Explainability – interprets how emotion-aware features influence predictions.  

## Technologies Used
- Programming Language: Python  
- Libraries: pandas, numpy, scikit-learn, nltk, keras, tensorflow, matplotlib, seaborn  
- Techniques: TF-IDF, Weighted TF-IDF, CNN, RNN, LSTM, Attention Mechanisms  
- Applications: Sentiment Analysis, Opinion Mining, Emotion-Aware NLP  

## Installation
Clone the repository  
`git clone https://github.com/gurleen-1/Enhancing-Language-Representation.git`  

Navigate to the project directory  
`cd Enhancing-Language-Representation`  

Install dependencies  
`pip install -r requirements.txt`  

## Usage
Run preprocessing and feature extraction  
`python preprocess.py`  

Train sentiment analysis model  
`python train_model.py`  

Evaluate performance (precision, recall, F1-score)  
`python evaluate.py`  

## Results
- Proposed Weighted TF-IDF Model achieved Precision: 91.54%, Recall: 92.82%, and F1-score: 92.18%, outperforming traditional methods such as CNN, RNN, and Naïve Bayes.  
- Demonstrated improved representation quality by incorporating emotional context into word features.  

## Contributing
Fork this repository  
Create a new branch  
`git checkout -b feature-branch`  
Commit your changes  
`git commit -m "Added new feature"`  
Push to the branch  
`git push origin feature-branch`  
Open a Pull Request  

## License
This project is licensed under the MIT License – see the LICENSE file for details.  
