IMDB Sentiment Analysis  

Jupyter notebook for sentiment analysis on the IMDB movie reviews dataset. Includes text preprocessing, exploratory analysis, and a baseline ML model.  

Features  
- Load IMDB dataset with Hugging Face `datasets`  
- Text cleaning & tokenization  
- EDA (word counts, frequent words, word clouds)  
- Sentiment classification (TF-IDF + Logistic Regression)  
- Evaluation (accuracy, confusion matrix, classification report)  

 Setup  

pip install -U datasets pandas numpy scikit-learn nltk matplotlib wordcloud langdetect joblib
jupyter notebook Text_Data_Exploration.ipynb
