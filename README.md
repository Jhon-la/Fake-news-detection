# Fake-news-detection
In this project, different natural language processing techniques and machine learning models were applied to classify news articles as fake or real, using Python’s scikit-learn library.
steps: 
The project begins with the implementation of preprocessing steps required to clean and prepare the input text data. The training, testing, and validation datasets are first loaded, followed by preprocessing techniques such as tokenization and stemming. Additionally, exploratory data analysis is conducted, including examining the distribution of the target variable and checking data quality issues such as missing or null values.

Next, feature extraction and selection techniques from Python’s scikit-learn library are applied. Methods such as bag-of-words, n-grams, and term frequency–inverse document frequency (TF-IDF) are used to represent the text data numerically. Other techniques like Word2Vec and part-of-speech (POS) tagging were explored for feature extraction, although they were not fully incorporated into the final model.

After feature engineering, multiple classification algorithms are trained to perform fake news detection. These include Naive Bayes, Logistic Regression, Linear SVM, and Random Forest classifiers. Each classifier is evaluated using the extracted features, and their performance is compared based on metrics such as F1-score and confusion matrices.

The top-performing models are then selected for further optimization. Hyperparameter tuning is carried out using GridSearchCV to identify the best parameter configurations. Finally, the best-performing model is chosen and used to classify news articles, providing predictions along with the probability of being true.

The final selected model with the best overall performance is Logistic Regression.
