# Amazon Reviews

### Abstract
In this project, I have worked on the Amazon cell phone reviews Dataset and have performed ExploratoryData Analysis, Topic Modelling to get a few insights. I am planning to use Amazon customer reviews on cell phones. There are other existing datasets on Amazon mobile/cell phones, but this dataset focuses on both unlocked and locked carriers and scoped on ten brands: ASUS, Apple, Google, HUAWEI, Motorola, Nokia, OnePlus, Samsung, Sony, and Xiaomi.

### Objective/What business problem I am trying to solve?
Sometimes, the customer’s star ratings are not the same as their comments. The main objective of this paper is to predict the ratings of the product from the text of the given review using TF-IF vectorization, LinearSVM classifier. Further, I experimented by remodeling it as a classification problem in which I tried classifying the reviews into positive and negative reviews.
Also I am going to extract the top most words used to describe particular problem so the company would know what are the terms that the user is actually using the most. Sometimes the star ratings are not enough, it is important to know the sentiments behind the customer’s review

### Introduction
Using an existing dataset of locked and unlocked phones sold on Amazon’s customer reviews for locked and unlocked phones, which is focused on 10 brands ASUS, Apple, Google, HUAWEI, Motorola, Nokia, OnePlus, Samsung, Sony, and Xiaomi. The dataset contains 82815 reviews for a period of roughly 15 years. 2 CSV files, items.csv with details of the product and reviews.csv  with details of the customer reviews were given in the datasets. All the ratings are for a corresponding Brand and Model, along with a numerical rating. 

### About the Dataset?
Using an existing dataset of locked and unlocked phones sold on Amazon’s customer reviews for locked and unlocked phones, which is focused on 10 brands ASUS, Apple, Google, HUAWEI, Motorola, Nokia, OnePlus, Samsung, Sony, and Xiaomi. The dataset contains 82815 reviews for a period of roughly 15 years. 2 CSV files, items.csv with details of the product, and reviews.csv  with details of the customer reviews were given in the datasets. All the ratings are for a corresponding Brand and Model, along with a numerical rating. 

### Where and How I got the data?
Published here are two files, items.csv and reviews.csv with a date prefixed which indicates when the data is retrieved.
items.csv contains retrieved (read: scraped) items from Amazon.com search results using generated URL and specific query string to search only specific brands and has minimal 1-star review.
reviews.csv contains reviews for previously retrieved items at items.csv but not with columns from items.csv.
Datasets are retrieved using Puppeteer.

### Know more about Puppeteer: 
[https://pptr.dev/#?product=Puppeteer&version=v7.1.0&show=api-overview](https://pptr.dev/#?product=Puppeteer&version=v7.1.0&show=api-overview)

### Step by step derivation of the dataset already performed:
[https://github.com/grikomsn/amazon-cell-phones-reviews](https://github.com/grikomsn/amazon-cell-phones-reviews)

### Structured/Unstructured Data: 
This dataset is a structured Dataset. 

### Methods that are going to be used:
- TF-ID vectorizer 
- LinearSVM classifier
- Logistic regression classifier 
-	MultinomialNB 
-	Topic Modelling

### References used for this project:
- [https://towardsdatascience.com/predicting-sentiment-of-amazon-product-reviews-6370f466fa73](https://towardsdatascience.com/predicting-sentiment-of-amazon-product-reviews-6370f466fa73) : There is a very situation in this project. They are trying to predict the reviews through the sentiments and find the precision and accuracy. The sentiments are deciding factors of whether the review is negative or positive. It is very useful for my projects but I will be using other vectorization techniques than this project.
- [https://towardsdatascience.com/review-rating-prediction-a-combined-approach-538c617c495c](https://towardsdatascience.com/review-rating-prediction-a-combined-approach-538c617c495c): This is also the same context but they have also used Random Forest, NLP, and decision tree to solve the same problem which can be very useful as I can try to solve the issue I am trying to tackle with NLP instead of TF-IF vectorization. It gives me choice as to which vectorization methods work for me.
- [https://www.developintelligence.com/blog/2017/03/predicting-yelp-star-ratings-review-text-python/](https://www.developintelligence.com/blog/2017/03/predicting-yelp-star-ratings-review-text-python/): This is a project from YELP reviews that are based on vectorization, they have some very easy method to test and train the data that i can use.


