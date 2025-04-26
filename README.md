
## Problem Statement

This project analyzes customer reviews for mobile phones and predicts the sentiment of each review as positive or negative. By using machine learning, the goal was to understand consumer sentiments and improve product feedback analysis. The project implements techniques like CountVectorizer, TF-IDF, and n-gram to vectorize the text data and uses Logistic Regression for sentiment classification.

## Tools and Libraries
- Python

- Libraries: Pandas, NumPy, Scikit-learn, Matplotlib (for visualizations)

- ML Model: Logistic Regression

- Techniques Used: CountVectorizer, TF-IDF, n-grams
# Key Steps
### *Data Loading:* 
The dataset contains information about customer reviews for mobile phones, including product names, brands, prices, ratings, and review content. I used a 10% sample of the data to reduce memory usage due to the large dataset size.

### *Text Vectorization:*
- CountVectorizer: This technique converts text data into numerical format where each word gets a count.

- TF-IDF: Assigns more weight to rare words and less to common ones.

- N-grams: Pairs consecutive words to capture local context, improving accuracy in sentiment detection.

### *Modeling:*

A Logistic Regression model was trained on the processed text data to classify sentiments.

AUC ROC Score was used to evaluate the model's performance, yielding scores of 87%-91% depending on the vectorization technique used.


## Future improvements:
- Data Augmentation: Techniques like SMOTE can be use to balance the dataset and improve classification performance.

- Model Expansion: Test other algorithms like Random Forest and XGBoost to see if they can provide better results.

- Data Cleaning: Improve preprocessing by handling noisy data, slang, and abbreviations more efficiently.
