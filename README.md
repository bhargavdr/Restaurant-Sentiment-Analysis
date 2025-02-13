# Restaurant Sentiment Analysis

## Overview
This project performs **sentiment analysis** on restaurant reviews using a **Naïve Bayes classifier** trained on a historic dataset. The model classifies new (fresh) reviews as **positive** or **negative**, helping restaurant owners gain insights from customer feedback.

## Project Structure

### **Datasets**
- `RestaurantReviews_Historic.tsv` - The training dataset containing labeled restaurant reviews.
- `RestaurantReviews_Fresh.tsv` - The dataset containing new restaurant reviews that will be labeled using the trained model.

### **Models & Pickled Files**
- `bow_sentiment_model.pkl` - Stores the **bag-of-words vectorizer** used for text transformation.
- `Classifier_sentiment_model.joblib` - Stores the **trained Naïve Bayes classifier model**, trained on the historic dataset.

### **Jupyter Notebooks**
- `Analysis_Model.ipynb` - Contains the **training pipeline** for building the sentiment analysis model.
- `Predictor.ipynb` - Loads the trained model and **predicts sentiments** for fresh reviews.

### **Output Files**
- `Predicted_Sentiments.tsv` - The **final output file** containing fresh reviews along with their predicted sentiment labels.
