## Overview:

  Welcome to the Credit Card Churn Prediction Repository! This project is a comprehensive exploration of predicting credit card churn using advanced machine learning techniques. Dive into the world of data-driven insights and predictive analytics to anticipate and prevent customer churn in the credit card industry. This repository serves as a valuable resource for understanding the application of machine learning in the finance sector, emphasizing the importance of proactive customer relationship management.

## 📊 Key Features:

Data Cleaning/Preprocessing: Conducted checks for missing and duplicate values, removed irrelevant columns/rows, performed label encoding on binary categorical features, and generated dummy variables for non-binary categorical features, ensuring optimal data quality for predictive modeling.

Machine Learning Models: Implementation of various supervised learning algorithms, including Naive Bayes, Decision Trees, Support Vector Machines, and K-Nearest Neighbors, to evaluate and predict customer churn.

Evaluation Metrics: Robust assessment metrics such as accuracy, precision, and recall to gauge the performance of each model and identify the most effective approach.

Data Visualization: Engaging visualizations to illustrate key patterns and factors influencing credit card churn, aiding in a deeper understanding of the predictive models.


## 💡 Objective:

  Our primary objective is to leverage supervised learning models for credit card churn prediction, determining whether a credit card customer is likely to remain with the service or opt to churn. This prediction will be based on input features, aiming to develop accurate and reliable tools for proactive management of customer retention. 



## 🛠️ Technologies Used:

Python: Leveraging the power of Pandas, NumPy, and Scikit-Learn. 
Jupyter Notebooks: Transparent and interactive documentation of the entire workflow.



## 📈 Results:

Decision Tree:

The Decision Tree model exhibits a commendable performance with an accuracy of 94%. Notably, when predicting customer churn, the precision is 80%, indicating that it is correct 80% of the time. Additionally, the classifier demonstrates a solid recall rate of 83%, correctly identifying 83% of all customers who actually churn. Overall, these findings underscore the effectiveness of the Decision Tree classifier in predicting and identifying churn customers.

Naive Bayes Classsifier:


The Gaussian Naïve Bayes model achieves an accuracy of 90%. When predicting customer churn, the precision is 61%, indicating correctness 61% of the time. Moreover, the classifier demonstrates a recall of 72%, correctly identifying 72% of all customers who actually churn. These findings highlight the overall effectiveness of the Gaussian Naïve Bayes classifier in predicting and identifying churn customers.


KNN Classifier:

The K-Nearest Neighbors (KNN) model achieves an accuracy of 89%. When predicting customer churn, the precision is 56%, indicating correctness 56% of the time. Additionally, the classifier demonstrates a recall of 71%, correctly identifying 71% of all customers who actually churn. These findings reflect the overall performance of the KNN classifier in predicting and identifying churn customers.

Support Vector Machine (SVM) Classifier:

The Support Vector Machine (SVM) model shows an accuracy of 84%. However, it is essential to note that both precision and recall are 0%, indicating that when predicting customer churn, the model does not correctly identify any instances. These findings suggest limitations in the performance of the SVM classifier for the task of predicting and identifying churn customers.


## Conclusions:

The Decision Tree outperformed the other classifiers, boasting the highest accuracy at 94%. Gaussian Naïve Bayes closely followed with an accuracy score of 90%, and K-Nearest Neighbors (KNN) achieved 89%. On the other hand, the Support Vector Machine (SVM) had the least accuracy among the four classifiers, recording an accuracy of 84%. The dataset underwent thorough cleaning and preparation to ensure its readiness for model evaluation. Four supervised learning classifiers were applied to the dataset, yielding accuracy, precision, and recall scores for each. Due to the dataset comprising only 16.1% of customers who churned, training the model for churn prediction posed challenges. Consequently, this led to lower precision and recall scores for churn customers. While Decision Tree and Gaussian Naïve Bayes achieved higher accuracy scores, SVM, despite its faster computation time compared to KNN, exhibited unsatisfactory precision and recall scores for predicting churn customers. For scenarios where computation time is crucial, Naïve Bayes followed by the Decision Tree classifier emerge as superior options due to their efficiency compared to SVM and KNN. To enhance Precision and Recall scores in identifying churn customers, one approach is to unsample the data specifically for churn instances. The collected data provides valuable insights for individuals in the banking industry, shedding light on crucial features such as income, education level, credit limit, etc., when addressing customer attrition. Banking managers can leverage the explored data to devise strategies aimed at preventing customers from leaving credit card services. Exploratory Data Analysis (EDA) findings enable them to draw conclusions about the demographics, including gender, age, marital status, etc., and tailor preventative measures and improved services accordingly.



## 🔗 Connect with Me:

LinkedIn: [Your LinkedIn Profile] 


## 🌐 Explore the Project: 

Delve into the code, datasets, and visualizations. Contributions and feedback are warmly welcomed!

Predict the future, empower your decisions! 💳✨
