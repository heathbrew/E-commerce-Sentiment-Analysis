# E-commerce Sentiment Analysis

## Description
In this project, I aim to perform sentiment analysis using a dataset from an e-commerce domain. The dataset consists of over 34,000 consumer reviews for Amazon brand products. It includes attributes such as brand, categories, primary categories, reviews.title, reviews.text, and sentiment labels (Positive, Negative, Neutral). My goal is to predict the sentiment or satisfaction of a purchase based on various features and review text.

## Dataset
The dataset provides a valuable resource for understanding sentiment and satisfaction levels in e-commerce. It contains a wide range of consumer reviews, covering different products and categories. The reviews are accompanied by relevant attributes and sentiment labels, enabling the development of sentiment analysis models.

## Project Tasks
### Week 1
In the first week, I focused on tackling the class imbalance problem in the dataset and gaining insights through exploratory data analysis. The tasks included:
- Conducting an exploratory data analysis (EDA) to understand the characteristics of positive, negative, and neutral reviews.
- Checking the class count for each sentiment class to identify any class imbalance issues.
- Converting the reviews into TF-IDF scores, a technique to represent textual data numerically.
- Training a multinomial Naive Bayes classifier and observing the impact of class imbalance on the classification results.
- Tackling the class imbalance problem through oversampling or undersampling techniques.
- Evaluating the models using precision, recall, F1-score, and AUC-ROC curve, with a focus on the F1-Score as the evaluation criteria.

### Week 2
In the second week, I delved into model selection and advanced techniques to improve sentiment classification. The tasks included:
- Applying multi-class Support Vector Machines (SVM) and neural networks for sentiment classification.
- Exploring ensemble techniques such as combining XGBoost with oversampled multinomial Naive Bayes.
- Engineering a feature called sentiment score and incorporating it into the models to evaluate its impact on performance and gain insights.
- Applying Long Short-Term Memory (LSTM) neural networks, a type of recurrent neural network, to capture sequential information in the reviews.
- Comparing the accuracy of neural networks with traditional machine learning algorithms.
- Determining the best settings for LSTM and experimenting with Gated Recurrent Units (GRU) to classify reviews as positive, negative, or neutral using techniques like Grid Search, Cross-Validation, and Random Search.

Moreover, I explored topic modeling techniques to gain insights into different aspects of the products and analyze clusters of similar reviews. Techniques like Latent Dirichlet Allocation (LDA) and Non-Negative Matrix Factorization (NMF) were used for topic modeling.

## Screenshots
Screenshots of relevant plots, classification results, topic clusters, and any other visual representations have been added to the README document to illustrate the analysis and findings.
![image](https://github.com/heathbrew/E-commerce-Sentiment-Analysis/assets/55629425/98033ca3-0199-4c96-bfba-9830bfd60ceb)

![image](https://github.com/heathbrew/E-commerce-Sentiment-Analysis/assets/55629425/9d99ee71-41e6-46b1-91f4-c163b642bc6f)
![image](https://github.com/heathbrew/E-commerce-Sentiment-Analysis/assets/55629425/901b6248-afff-4739-be92-100f7bdf26ed)
![image](https://github.com/heathbrew/E-commerce-Sentiment-Analysis/assets/55629425/d3c79f08-ed1c-49ea-931c-3acda617fe24)


![image](https://github.com/heathbrew/E-commerce-Sentiment-Analysis/assets/55629425/68083f7e-2970-40e9-84ce-fa926fb009db)
![image](https://github.com/heathbrew/E-commerce-Sentiment-Analysis/assets/55629425/4e4ec6fe-9ea7-4a5b-a220-51ccf08ed392)
![image](https://github.com/heathbrew/E-commerce-Sentiment-Analysis/assets/55629425/90893775-13b3-4435-8e0e-0868923de887)


![image](https://github.com/heathbrew/E-commerce-Sentiment-Analysis/assets/55629425/ef27ff80-390a-45b9-be98-1039625dd33d)
![image](https://github.com/heathbrew/E-commerce-Sentiment-Analysis/assets/55629425/ae652abf-98ec-43e7-a6cf-a3c96f273cd5)
![image](https://github.com/heathbrew/E-commerce-Sentiment-Analysis/assets/55629425/6fc7d5bc-e35c-441f-9947-c3242ecaf318)

