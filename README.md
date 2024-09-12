# SOSH_AURA
Developed a hybrid predictive model on social media addiction and stress among Indian youth, utilizing K-Means clustering and Random Forest for engagement prediction, and behavioral analysis using Decision Tree and Random Forest Regressors.
Here is a README file template for your **Social Media Addiction and Engagement Prediction** project based on the provided information:

---

# **Social Media Addiction and Engagement Prediction**

This project investigates the correlation between social media usage and its potential impact on mental health, focusing on addiction patterns, user engagement, and psychological consequences. The data-driven study uses machine learning techniques to predict social media addiction and engagement levels, and examines the factors influencing user behavior.

## **Table of Contents**
- [Introduction](#introduction)
- [Features](#features)
- [Dataset](#dataset)
- [Technologies Used](#technologies-used)
- [Methodology](#methodology)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Future Scope](#future-scope)
- [Contributors](#contributors)
- [License](#license)

---

## **Introduction**

Social media addiction has become an increasing concern among teenagers and young adults, with potential links to mental health disorders such as anxiety, depression, and social isolation. This project employs data analysis and machine learning to predict user addiction levels based on their behavior, while also examining the negative effects on productivity and overall well-being. Various psychological factors, such as low self-worth and disrupted sleep patterns, are explored in relation to social media usage.

---

## **Features**

- **User Addiction Prediction**: Uses machine learning models to predict social media addiction based on user engagement and behavior.
- **Psychological Impact**: Identifies key indicators of mental health issues, such as anxiety, depression, and low self-esteem, linked to social media use.
- **Engagement Analysis**: Analyzes factors such as total time spent, number of sessions, and scroll rate to gauge user engagement.
- **Data Visualization**: Visual representations of the relationship between social media usage and productivity loss, satisfaction, and mental health.

---

## **Dataset**

The dataset used in this project has been sourced from a Kaggle repository: [Time Wasters on Social Media](https://www.kaggle.com/datasets/muhammadroshaanriaz/time-wasters-on-social-media). It simulates real-world data of social media interactions through synthetic data techniques.

### **Key Features of the Dataset**
- **User Demographics**: Age, gender, income, profession, and location.
- **Social Media Engagement**: Total time spent, number of sessions, video category, and scroll rate.
- **Mental Health Indicators**: Self-control, addiction level, satisfaction, and productivity loss.
- **Devices and Platforms**: Device type, OS, and platform usage (e.g., Facebook, Instagram, X, Snapchat).

---

## **Technologies Used**

- **Programming Languages**: Python
- **Libraries**: 
  - **Data Analysis**: NumPy, pandas
  - **Machine Learning**: Scikit-learn
  - **Visualization**: Matplotlib, Seaborn
- **Development Environment**: Jupyter Notebook

---

## **Methodology**

1. **Data Preprocessing**:
   - Data cleaning and preprocessing were performed using pandas.
   - Synthetic data was generated to replicate real-world social media behavior for analysis.

2. **Exploratory Data Analysis (EDA)**:
   - Visualizations were created to identify trends between social media use and mental health indicators.
   
3. **Clustering & Classification**:
   - K-Means clustering was used to segment users based on engagement patterns.
   - Random Forest classification was applied to predict user addiction and productivity loss.

4. **Model Evaluation**:
   - The model's performance was evaluated using accuracy, precision, and recall metrics.

---


## **Results**

The model successfully predicts user addiction levels based on engagement behavior, with a notable correlation between high social media usage and mental health issues like anxiety and low self-esteem. The K-Means clustering identifies distinct user groups, while the Random Forest model predicts addiction with an accuracy of XX%.

---

## **Future Scope**

- **Expanded Features**: Incorporating additional social media platforms and real-time data to enhance prediction accuracy.
- **User Personalization**: Offering personalized recommendations to reduce screen time and improve mental well-being.
- **Further Psychological Research**: Delving deeper into how specific social media activities (e.g., gaming, browsing) impact different mental health aspects.

