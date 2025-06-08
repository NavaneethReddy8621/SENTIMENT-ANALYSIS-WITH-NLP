# SENTIMENT-ANALYSIS-WITH-NLP
My project is a simple notebook that shows you how to perform sentiment analysis on customer reviews using TF-IDF vectorization and Logistic Regression.

What’s Inside?
-Data Preprocessing: Cleaning and preparing customer review text for analysis.
-Feature Extraction: Turning words into numbers using TF-IDF.
-Modeling: Training a Logistic Regression model to classify reviews as positive or negative.
-Evaluation: Checking how well our model performs with accuracy, precision, recall, and a confusion matrix.
-Demo Predictions: Try out the model on your own sample reviews!

Commands to run project:

-->>pip install pandas scikit-learn matplotlib seaborn

Open the notebook in Jupyter.
Run the cells one by one. You’ll see results print out and plots appear as you go.

Note: You can also replace the sample data section with your own CSV file (make sure it has columns named review and sentiment).

CLASSIFICATION REPORT:

Accuracy: 0.87

              precision    recall  f1-score   support

    Negative       0.89      0.85      0.87        20
    Positive       0.86      0.90      0.88        20

    accuracy                           0.88        40
   macro avg       0.88      0.88      0.88        40
weighted avg       0.88      0.88      0.88        40


A blue-shaded grid showing how many reviews were correctly or incorrectly classified as positive or negative. This helps you quickly spot where the model is making mistakes




