# Urdu Sentiment Analysis Project

## Description
This project aims to perform sentiment analysis on Urdu text data, focusing on the detection of sarcasm. The model is designed to classify sentiments expressed in social media posts, enabling insights into public opinion and emotion.

## Project Phases
1. **Data Preprocessing**: Cleaned the text data by removing noise and applying lemmatization.
2. **Feature Extraction**: 
   - **Tokenization**
   - **TF-IDF Vectorization** 
   - **Word2Vec** for word embeddings.
3. **Model Building**: 
   - Built and trained a classification model to predict sentiments.
4. **Evaluation**: Assessed the model's performance using various metrics.

## Accuracy
- The model achieved an accuracy of **78.6%**.
  
## Challenges in Urdu Sentiment Analysis
1. **Complex Morphology**: Urdu has a rich morphology, making it difficult to standardize words and their meanings.
2. **Colloquial Language**: Social media posts often contain informal language and slang, which complicates the sentiment analysis process.
3. **Noisy Data**: Data collected from social media can include irrelevant information, making it necessary to filter and clean effectively.

## Conclusion
This project demonstrates the effectiveness of machine learning models in understanding sentiments expressed in Urdu text. Further improvements can be made by enhancing data preprocessing techniques and exploring advanced models.

## Getting Started
To run this project, ensure you have all the required packages installed. You can use the following command to install them:

```bash
pip install -r requirements.txt
