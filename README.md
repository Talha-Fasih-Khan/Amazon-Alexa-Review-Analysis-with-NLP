# Amazon-Alexa-Review-Analysis-with-NLP

#### -- Project Status: [Completed]

## Project Intro/Objective
The purpose of this project was to perform sentiment analysis on Amazon Echo reviews to gain insights into customer satisfaction and identify sentiments associated with various product features. Natural language processing (NLP) techniques and machine learning algorithms were employed to build, train, test, and deploy an AI model for sentiment prediction.

### Methods Used
* Inferential Statistics
* Machine Learning
* Data Visualization
* Predictive Modeling
* etc.

### Technologies
* Python
* Pandas, jupyter
* etc.

## Project Description
* Data Collection
  * A dataset containing 3,150 customer reviews for Amazon Echo devices was collected from Amazon's website. The dataset included attributes such as rating, date, variation (color/type of Echo), verified reviews, and feedback (0 for negative, 1 for positive). The dataset was manually collected for this project.
* Data Preprocessing
  * Text preprocessing techniques were applied to the collected dataset. This included lowercasing the text, tokenization, and removal of stopwords and special characters. The NLTK library was utilized to implement these preprocessing steps.
* Methodology
  * The following methodologies were employed for sentiment analysis:
    * Exploratory Data Analysis (EDA): Numpy, Pandas, Seaborn, and Matplotlib were used to perform exploratory data analysis. This step provided an overview of the dataset and helped identify any patterns or trends.
    * Feature Extraction: The verified reviews were selected as the primary feature for sentiment analysis. Count vectorization was applied to convert the textual data into a numerical format suitable for analysis. This transformation enabled the utilization of machine learning algorithms.
    * Model Training and Evaluation: Three models were trained and evaluated: The naive Bayes classifier, the logistic regression model, and the gradient boosting classifier. The scikit-learn library was utilized for model implementation. The training data was split into a training set and a test set. Classification reports and confusion matrices were used to evaluate the performance of each model.
    * Word Clouds: Word clouds were created to visualize the most frequently used words in the Amazon Echo reviews. This helped identify common themes or sentiments expressed by customers.
