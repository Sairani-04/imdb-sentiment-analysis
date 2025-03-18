# Sentiment Analysis of IMDB Movie Reviews (Natural Language Processing)

## Project Overview  
This project analyzes sentiment (positive/negative) in IMDB movie reviews using Natural Language Processing (NLP). The model classifies reviews based on their sentiment, helping businesses and individuals gauge public opinion on movies.  

## Technologies Used  
- Python  
- TensorFlow/Keras (for deep learning model)  
- NLTK & SpaCy (for text preprocessing)  
- Scikit-Learn (for evaluation & preprocessing)  
- Matplotlib & Seaborn (for data visualization)  

## Project Structure  
**imdb-sentiment-analysis**  
- **sentiment_analysis.ipynb** – Jupyter Notebook with model training & evaluation  
- **imdb_reviews.csv** – Dataset (IMDB reviews with sentiment labels)  
- **README.md** – Project documentation  
- **requirements.txt** – Python dependencies  

## How to Run  

### Clone the Repository  
```bash
git clone https://github.com/<your-username>/imdb-sentiment-analysis.git  
cd imdb-sentiment-analysis  
```

### Install Dependencies  
```bash
pip install -r requirements.txt  
```

### Open the Jupyter Notebook  
```bash
jupyter notebook sentiment_analysis.ipynb  
```

## Model Performance  
- Best Model: LSTM-based deep learning model  
- Training Accuracy: 92.37%  
- Validation Accuracy: 90.07%  
- Loss: 0.2093 (train), 0.2701 (validation)  

## Next Steps  
- Improve accuracy using hyperparameter tuning  
- Experiment with BERT or Transformer models  
- Deploy as a Flask API for real-time sentiment analysis  

## License  
This project is open-source and available under the MIT License.  

Feel free to fork, contribute, or provide suggestions.

