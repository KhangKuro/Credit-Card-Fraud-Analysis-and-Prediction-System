![](https://github.com/KhangKuro/Credit-Card-Fraud-Cluster/blob/main/CCF.png)

# Credit Card Fraud Analysis and Prediction System 💳🕵️‍♂️

## Introduction 🌟

In the digital age, financial transactions are increasingly vulnerable to fraud. Credit card fraud is a major concern for financial institutions and consumers alike. This project, the Credit Card Fraud Analysis and Prediction System, aims to tackle this challenge by analyzing transaction data, identifying patterns of fraudulent behavior, and developing predictive models to detect fraud. Our comprehensive approach integrates data processing, machine learning, and data visualization to enhance the detection and prevention of credit card fraud.

## About the Dataset ℹ️

This dataset simulates credit card transactions, including both legitimate and fraudulent transactions, from January 1, 2019, to June 31, 2020. It includes information on transactions of 1000 customers using credit cards with a group of 800 service providers.

- [Kaggle - Credit Card Transactions Fraud Detection Dataset](https://www.kaggle.com/datasets/kartik2112/fraud-detection/data)

### Data Description 📝

- **trans_date_trans_time**: Date and time of the transaction.
- **cc_num**: Customer's credit card number.
- **merchant**: Service provider the customer is paying (e.g., Amazon, Walmart).
- **category**: Category of the transaction.
- **amt**: Amount of the transaction.
- **first, last**: Customer's first and last name.
- **gender**: Customer's gender.
- **street, city, state**: Customer's address.
- **zip**: Zip code of the transaction.
- **lat, long**: Customer's latitude and longitude.
- **city_pop**: Population of the city where the customer lives.
- **job**: Customer's occupation.
- **dob**: Customer's date of birth.
- **trans_num**: Unique transaction number for each transaction.
- **unix_time**: Transaction time in Unix format (usually not used in analysis due to uniqueness).
- **merch_lat, merch_long**: Latitude and longitude of the merchant.
- **is_fraud**: Binary index indicating whether the transaction is fraudulent (1 for fraud, 0 for not fraud).

![Entity Relationship Diagram](https://github.com/KhangKuro/Credit-Card-Fraud-Detection/blob/main/erd.png)
*Description: Entity Relationship Diagram illustrating the structure and relationships within the dataset.*

## System Workflow Overview 🛠️

![System Workflow](https://github.com/KhangKuro/Credit-Card-Fraud-Analysis-and-Prediction-System/blob/main/Flow%20Chart.jpg)
*Description: Comprehensive workflow chart showing the various steps involved in the credit card fraud analysis and prediction system.*

## Data Processing and Storage 🗄️

### Data Source and Processing

The data is sourced from Kaggle and includes customer information and credit transactions. Initial data processing involves cleaning and preparing the data for analysis.

### Data Storage

A PostgreSQL database is used to store the cleaned data, including customer information, credit transactions, and flagged transaction classifications.

![Data Storage](https://github.com/KhangKuro/Credit-Card-Fraud-Cluster/blob/main/CCF.png)
*Description: Visual representation of the data storage process, highlighting the key components and their interactions.*

## Detection Model 🕵️‍♀️

### Imbalance Handling

Imbalance handling algorithms are applied to address the issue of disproportionate fraud vs. non-fraud transactions.

### Machine Learning & Deep Learning

Various machine learning and deep learning models are trained and fine-tuned to create an effective fraud detection model.

### Model Training

Models are trained on the processed data, with an emphasis on fine-tuning to enhance detection accuracy.

![Detection Model](https://github.com/KhangKuro/Credit-Card-Fraud-Cluster/blob/main/CCF.png)
*Description: Diagram depicting the detection model workflow, including imbalance handling and model training steps.*

## Customer Segmentation 👥

### Perform Clustering

Clustering algorithms are used to find optimal clusters within the transaction data, identifying distinct customer segments.

### Segment Extraction

Extract and visualize segments to create detailed profiles for each cluster, aiding in targeted fraud detection strategies.

### Insight Analysis

Perform in-depth analysis of each customer segment to gain insights into their behavior and fraud patterns.

![Customer Segmentation](https://github.com/KhangKuro/Credit-Card-Fraud-Cluster/blob/main/CCF.png)
*Description: Illustration of the customer segmentation process, from clustering to insight analysis.*

## Data Visualization & Analytics 📈

### Dashboard Design

Using BI tools like Tableau, interactive dashboards are created to visualize transaction data and fraud detection insights.

### Analysis & Storytelling

Data is analyzed and presented in a storytelling format to provide clear and actionable insights to stakeholders.

![Data Visualization](https://github.com/KhangKuro/Credit-Card-Fraud-Cluster/blob/main/CCF.png)
*Description: Example of a data visualization dashboard designed to highlight key insights and trends.*

## Synthesis & Conclusion 📝

### Extract Insights

Detailed insights are extracted from the analysis, highlighting key patterns and trends in fraudulent transactions.

### Compare & Synthesize

Compare findings with existing literature and synthesize the results to formulate effective fraud prevention strategies.

### Report & Recommend

Create a comprehensive report with recommendations for financial institutions to implement enhanced security measures.

![Synthesis & Conclusion](https://github.com/KhangKuro/Credit-Card-Fraud-Cluster/blob/main/CCF.png)
*Description: Visual representation of the synthesis and conclusion process, summarizing the key steps and outcomes.*

## Additional Resources 📚

For more detailed analyses and further information, please visit the following repositories:

- [Credit-Card-Fraud-Analysis](https://github.com/KhangKuro/Credit-Card-Fraud-Analysis)
- [Credit-Card-Fraud-Detection](https://github.com/KhangKuro/Credit-Card-Fraud-Detection)

Thank you for exploring our Credit Card Fraud Analysis and Prediction System. We hope this information helps in enhancing your understanding and implementation of effective fraud detection strategies.

## Contact 📞

For any queries or further information, please contact:

- **Email:** hbaokhangofficial@gmail.com
- **Phone:** +84 349 429 011

Thank you! 💳🕵️‍♂️
