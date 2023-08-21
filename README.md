# Articles-Text-Classification-Hespress-Dataset
## Steps involved in the training process:
1) The dataset was collected from multiple CSV files, 1 for each topic, containing stories data from the Hespress dataset. The data was split into training and test sets, with the last 20% of each file used for testing.
   
2) The text data was cleaned, processed and prepared for training. This included removed diacritics, special characters, normalized the text to lowercase, tokenized the text, removed stop words, and stemmed the remaining words. Then seperated train and test data.
   
3) Three classification models were used in this analysis: Logistic Regression, Linear Support Vector Classifier (LinearSVC), and Support Vector Classifier (SVC). For each model, a pipeline was created, including a TF-IDF vectorizer for text representation and the chosen classifier.

4) The accuracy scores and classification reports were generated for each model using the test data to evaluate their performance. The classification report includes precision, recall, F1-score, and support for each class. A confusion matrix was created to visualize the model's performance in classifying each class.

5) Some potential enhancements to achieve better results were suggested, including collecting more data, advanced feature engineering, hyperparameter tuning, and trying more advanced algorithms like deep learning models.

The best model, SVC, achieved an accuracy of approximately 85.32% on the test data.
