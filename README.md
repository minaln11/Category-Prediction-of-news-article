**# Category-Prediction-of-news-article** 

**News Category Classification using Naive Bayes**
This project focuses on building a Naive Bayes classifier to predict the category of news articles based on their headlines and publishers. The dataset used for this task is the News Aggregator Dataset, collected from various news sources like Reuters, CNN, etc., spanning from March 10th to August 10th in the year 2014. The features of the dataset include headlines, URLs, publishers, categories (business, science and technology, entertainment, health), and timestamps.

*Research Question and Approach*

The main research question is to predict the category of news articles with the highest possible accuracy using the Naive Bayes algorithm. Since Naive Bayes is a probabilistic supervised learning algorithm, it's well-suited for text classification tasks and can handle high-dimensional data like text efficiently. To answer the research question, the project involves preprocessing the text data, stemming, and removing stop words to prepare it for model training. The Naive Bayes classifier is then trained on the preprocessed data.

*Parameter Tinkering*

The project explores various parameter tinkering techniques to improve the model's accuracy. Three different approaches are tested:
Tinkering with the maximum number of features: Experimenting with the number of features considered in the vectorization process using TfidfVectorizer.
Using different vectorizers: Comparing the performance of the Naive Bayes model with CountVectorizer instead of TfidfVectorizer.
Varying alpha value: Adjusting the smoothing parameter alpha to handle low-frequency words in the dataset.


*Results and Visualization*

The accuracy of each model is calculated and compared to the default Naive Bayes model. The performance is visualized using a bar graph that shows the accuracy of the different models side by side.
