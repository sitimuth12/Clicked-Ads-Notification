# MinPro-Clicked-Ads-Notification
Predict Clicked Ads Customer Classification by using Machine Learning

## Problem
Tim bisnis ingin mengoptimalkan metode cara beriklan mereka di platform digital agar mendapatkan user yang potential untuk click sebuah product. Agar cost yang dikeluarkan tidak terlalu besar.

## Goals
Membuat machine learning model yang dapat mendeteksi potential user untuk convert atau tertarik pada sebuah iklan. Sehingga kita bisa mengoptimalkan cost dalam beriklan di platform digital.

## Steps
1. Exploratory Data Analysis (Descriptive, Univariate, Multivariate)
2. Data Preprocessing (Handle Missing Value, Extract Datetime Data, Split Target dan features, dan Feature Encoding)
3. Train model with 5 different algorithms classification with data default and normalize data
4. Evaluation with confussion matrix
5. Business Recomendatio

## Analisis Data
1.Distribusi pada kolom Clicked Ads (target) sudah Balanced
![alt text](?raw=true)

2. User yang berpotensi merespon iklan perusahaaan terdapat pada orang tua
![alt text](?raw=true)

3. Potensi user yang merespon ditemukan pada user yang berpendapatan lebih rendah dibandingkan yang tidak merespon.
![alt text](?raw=true)

4. Potensi user yang merespon lebih tinggi untuk user yang jarang menggunakan internet dibandiangan dengan user yang sering menggunakan internet.
![alt text](?raw=true)

## ML Modeling
Before train the model, split the data into train set & test set (size is 30%). Trained the model with 5 different algorithms and evaluated them with Accuracy. The reason is to predict whether a data is included in the positive or negative class and and the data is balance.
![alt text](?raw=true)
The result we choose the Random Forest model as the best model because it has the best-fit accuracy compared to other models.

## Model Evalutaion
![alt text](?raw=true)
By using the confusion matrix, it is obtained that the resulting Random Forest model is very good. We can see the prediction error (purple cells) is very small (top right and bottom left).

## Business Insight & Recomendations
Insight:
1. The data obtained has 2 user segments, namely active user and non-active user segments.
    - Active users have the criteria of frequently using the internet, frequently visiting a product's website, having a relatively young age and high income.
    - Non-active users have the opposite nature.
2. Non-active users, tend to be more easily attracted to clicks product on digital ads.
3. Users who frequently use the internet are more difficult to advertise because they may be used to digital ads.
4. Parents are a potential market for the digital market.

Recommendation:
1. We can use a more unique method (soft selling) so that users don't see advertising as much.
2. Use simple content to hook users with non-active user segments.
