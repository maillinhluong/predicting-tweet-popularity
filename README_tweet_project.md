# Predicting Tweet Popularity

This project uses logistic regression and sentiment analysis to predict whether a tweet will receive high engagement.

## 📂 Project Structure
- `tweet_model.ipynb` – Jupyter Notebook containing the full data pipeline and model
- `data/tweets.csv` – Sample dataset of tweets
- `visuals/accuracy.png` – Model performance visualization

## 🧠 Tools Used
- Python
- Pandas, Scikit-learn, VADER Sentiment
- Logistic Regression
- Matplotlib, Seaborn

## 🧪 Key Steps
1. Cleaned and merged multiple tweet datasets (10K+ entries)
2. Engineered features: hashtag count, sentiment score, user influence
3. Trained logistic regression model to classify engagement
4. Evaluated model with 85% accuracy

## 📊 Insights
- Positive sentiment and use of specific hashtags increase engagement probability
- User follower count was a significant predictor

## 🚀 Future Improvements
- Integrate Twitter API for real-time predictions
- Explore NLP-based classification with transformers