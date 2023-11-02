# Big data in Telecom : classification and analysis of tweets

## Problem statment

Telecom network often encounters large number of tweets based on the user experience for a network. This huge amount of raw data can be used for industrial or business purpose by organizing according to our requirement.

## Aim

This project aims to address the social media review challenges for the telecom companies by extracting the tweets, analyzing them and seperating them into various categories to help the company understand the concerns of their customers and thereby, save millions and prevent customer loss.

## Implementation

Examining Large amount of Verizon page tweets extracted from Twitter for a period of 4 days using hashtag #Verizon.

Classifying the tweets into different labels based on the user experience for the network.

Developing Model using Machine Learning algorithm to classify the tweets and evaluate the model.

Converting the text to lower case.

Used TFIDF to perform feature vectorization method widely used in text mining to reflect the importance of a word to a text.

Term frequency-inverse document frequency (TF-IDF) is a feature vectorization method widely used in text mining to reflect the importance of a term to a document in the corpus.

We have implemented Random Forest model using Pyspark MLlib. The ensemble model makes predictions by combining results from the individual trees. 

# Visualizations

Count of Tweets under various category             |  Pie Chart to demonstrate the percentage of tweets under various category
:-------------------------:|:-------------------------:
<img width="309" alt="image" src="https://user-images.githubusercontent.com/73183258/166132057-3addc043-2e18-4847-b3bd-3a4ca604ab8a.png">  |  <img width="402" alt="image" src="https://user-images.githubusercontent.com/73183258/166132059-bba6c989-6c5b-48f8-85aa-83a1da9bcc72.png">

Sentiment Analysis             |  Word Cloud for the tweets
:-------------------------:|:-------------------------:
<img width="385" alt="image" src="https://user-images.githubusercontent.com/73183258/166131910-07d2d342-7f97-4822-801e-e7a6bc6e43dc.png">  | <img width="425" alt="image" src="https://user-images.githubusercontent.com/73183258/166131912-7809fee5-54a9-4d40-9b9d-a41398bdc544.png">

* Model Accuracy and Evaluation

<img width="848" alt="image" src="https://user-images.githubusercontent.com/73183258/166131926-d7aff902-fc77-465a-a5b6-545cf73d0d36.png">

# Recommendations

From our analysis we can say that Verizon must focus on their service (which includes customer service and Network issues). 
By focusing on these issues they can improve their customer satisfaction and avoid loss( which is also visible in the plots)
We can also see around  12.5% of people are willing to join Verizon( New potential customers)
They can use this information and make sure their marketing expenditure is used to attract these customers.



