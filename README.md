# Customer Satisfaction Analysis for an Airline Company
Developed as a part of Statistics course at Universiry of Delhi, Lady Shri Ram College.
Created by Tanvi Saini, Narayanam Sai Lakshmi Jayani, and Ishwinder Kaur.

## Overview
This project analyzes customer satisfaction in the airline industry, identifying key factors that influence passenger experiences. Using a dataset from Kaggle, we applied multiple machine learning models—Logistic Regression, Decision Trees, and Naïve Bayes—to predict customer satisfaction based on flight-related and service-related attributes.

The goal is to help airlines improve customer service by identifying key areas affecting passenger satisfaction, optimizing service strategies, and reducing negative feedback.

## Motivation
The airline industry is highly competitive, and customer satisfaction plays a crucial role in brand reputation, customer retention, and financial success. Airlines must focus on service quality, complaint management, and passenger expectations to maintain customer loyalty.

With the rise of social media, a single negative experience can go viral, damaging a company’s reputation. This project provides data-driven insights to help airlines:<br>
✔ Identify key service factors that drive satisfaction.<br>
✔ Improve service quality in crucial areas like seat comfort, inflight entertainment, and baggage handling.<br>
✔ Predict and classify customer satisfaction levels for better decision-making.

## Data Sources & Feature Engineering
📊 Dataset: Passenger Satisfaction for a US Airline
🔗 Dataset Link

### Key Features:
* Demographics: Gender, Age, Customer Type, Type of Travel, Class
* Service Quality Factors: Seat Comfort, Online Support, Inflight Entertainment, Baggage Handling, Cleanliness
* Flight Details: Flight Distance, Departure Delay, Arrival Delay
* Satisfaction (Target Variable): Satisfied (Yes/No)
### Feature Engineering:
- Handling Missing Values – Logical imputation for NA values.
- Categorical Encoding – Dummy variables for categorical features.
- Correlation Analysis – Removed highly correlated redundant variables.

## Modeling Approach
We implemented and compared three machine learning models to predict customer satisfaction:

- Logistic Regression – Simple and interpretable model for binary classification.
- Decision Tree (CART) – Best-performing model; provides better classification and insights into key decision factors.
- Naïve Bayes – Probabilistic approach with good generalization.
<br>
📌 Best Model: Decision Tree (CART) <br>
📊 Accuracy: 86.54%<br>
🎯 Sensitivity: 90.03% (Correctly identified satisfied customers)<br>
🎯 Specificity: 82.31% (Correctly identified dissatisfied customers)<br>

## Key Insights & Recommendations
Our analysis found that the most significant factors affecting customer satisfaction include:

### 1️⃣ Seat Comfort
🔹 Impact: Customers who rated seat comfort 5/5 had a 99.2% satisfaction rate.<br>
✅ Recommendation: Airlines should invest in comfortable seating to improve overall satisfaction.

### 2️⃣ Inflight Entertainment
🔹 Impact: 96.2% of passengers who rated inflight entertainment highly were satisfied.<br>
✅ Recommendation: Enhance movie, music, and WiFi options for better passenger experience.

### 3️⃣ Online Support & Service
🔹 Impact: 77.3% satisfaction for high-rated online support services.<br>
✅ Recommendation: Improve customer service response times and digital support platforms.

### 4️⃣ Flight Delays & Baggage Handling
🔹 Impact: Baggage handling and flight delays were negatively correlated with satisfaction.<br>
✅ Recommendation: Optimize luggage handling systems and reduce delays to enhance customer experience.

## Deployment & Future Enhancements
### Current Impact:<br>
✔ Provides airlines with actionable insights to improve passenger experience.<br>
✔ Predicts dissatisfied customers, allowing airlines to address concerns proactively.<br>
✔ Improves airline service strategies using data-driven decision-making.

### Future Scope:<br>
🔹 Deep Learning Integration – Implement Neural Networks for higher predictive accuracy.<br>
🔹 Sentiment Analysis – Analyze customer reviews for deeper insights into complaints.<br>
🔹 Dynamic Pricing Strategies – Explore how pricing affects satisfaction and retention.
