
# Project Title

Project Overview: Customer Sentiment Analysis for Restaurant Management
Purpose:
The primary goal of this project is to assist restaurant management in understanding customer satisfaction through the analysis of customer reviews. By evaluating these reviews, management can identify areas of improvement and avoid repeating mistakes, ultimately enhancing the overall dining experience.

Target Audience:
This project is designed for restaurant managers and owners who want to gain insights into customer sentiments. It can also be beneficial for marketing teams and customer service departments aiming to improve customer relations and service quality.

Project Description:
The project involves analyzing customer reviews to determine whether they are positive or negative. This sentiment analysis helps in understanding the emotions of the customers and provides actionable insights. The following Python libraries are utilized to achieve the project's objectives:

Pandas: For data manipulation and analysis.
CountVectorizer: For converting text data into numerical data (vectorization).
RandomForestClassifier: For classifying the reviews based on the sentiment.
Steps Involved:

Data Reading and Preparation:

The customer reviews are read from a CSV file using Pandas.
The data is stored in a Pandas DataFrame for easy manipulation and analysis.
Data Preprocessing:

Handling Missing Values: Any missing values in the dataset are appropriately handled to ensure the integrity of the data.
Text Normalization: The text data is cleaned by replacing special characters, converting all text to lowercase, and removing any unnecessary whitespace.
Binary Classification: The reviews are categorized into binary values "0" and "1" based on the column ‘liked’. Here, "1" represents a positive review and "0" represents a negative review.
Feature Extraction:

CountVectorizer is used to convert the text data into a matrix of token counts. This step is crucial for transforming textual data into numerical data that can be processed by machine learning algorithms.
Model Training and Evaluation:

A RandomForestClassifier is trained on the processed data to classify the reviews into positive or negative sentiments.
The model is evaluated to ensure accuracy and reliability in predicting the sentiment of new reviews.
Sentiment Analysis:

When a new review is analyzed, the model returns "Positive review" if the sentiment is favorable, and "Negative review" if the sentiment is unfavorable.
Conclusion:
By implementing this project, restaurant management can gain valuable insights into customer satisfaction. This sentiment analysis tool helps in identifying trends and areas for improvement, ultimately leading to a better dining experience for customers. The use of Python and its powerful libraries ensures that the analysis is efficient and accurate.
