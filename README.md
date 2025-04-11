This project involves building an Email Spam Detector that classifies email messages as either spam or ham (non-spam) using Natural Language Processing (NLP) and Machine Learning techniques. The main goal is to automate the detection of unsolicited or harmful emails to enhance communication safety and efficiency.

The dataset used in this project consists of labeled emails with two categories: "spam" and "ham." The raw data undergoes preprocessing to ensure consistency—this includes text cleaning and label normalization. The email text is then transformed into a numerical format using the Bag-of-Words model via CountVectorizer, which converts textual data into a matrix of token counts suitable for machine learning.

For classification, a Multinomial Naive Bayes algorithm is employed due to its effectiveness in handling discrete data like word counts. The dataset is split into training and testing sets to evaluate the model's performance. After training, the model's accuracy and classification report (precision, recall, F1-score) are computed to assess how well it distinguishes spam from ham emails.

The system also includes a prediction function that can classify new, unseen emails in real-time. This enables users to input any email content and receive an instant classification result.

This project demonstrates key concepts in NLP, including text vectorization, supervised learning, and binary classification. It serves as a foundational step toward more advanced AI applications like intelligent email filtering, sentiment analysis, and chatbot development.
