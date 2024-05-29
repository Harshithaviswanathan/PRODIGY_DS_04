# PRODIGY_DS_04

The primary goal of the provided code is to enhance the understanding and management of customer feedback on social media platforms,here Twitter. 

By analyzing the sentiment of tweets, businesses and organizations can identify and address negative sentiments, thereby improving customer satisfaction and brand reputation. This process involves several steps, including loading and preprocessing the data, conducting exploratory data analysis to uncover key patterns, and visualizing the results to gain actionable insights. Ultimately, the aim is to use this information to create strategies that can eradicate negative sentiments and promote positive engagement with customers.

Data Preprocessing:

Cleaned the tweet text by removing special characters, numbers, and short words.

Tokenized and stemmed words to normalize the text data.


Exploratory Data Analysis (EDA):

Visualized word clouds to understand the frequency of words in tweets.
Analyzed sentiment distribution to identify the prevalence of positive, negative, and neutral sentiments.
Investigated tweet length by sentiment to uncover potential patterns.


Feature Extraction:

Converted text data into numerical features using TF-IDF vectorization, enabling machine learning algorithms to process the data.


Model Training and Evaluation:

Trained a Logistic Regression model on the training data to classify sentiment.
Evaluated the model's performance using accuracy, precision, recall, and F1-score metrics.
Displayed a confusion matrix to visualize the model's classification performance.


Prediction on New Data:

Applied the trained model to predict sentiments on a new dataset, facilitating sentiment analysis on unseen data.





