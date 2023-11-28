Welcome to the Credit Card Churn Prediction Repository! This project is a comprehensive exploration of predicting credit card churn using advanced machine learning techniques. Dive into the world of data-driven insights and predictive analytics to anticipate and prevent customer churn in the credit card industry.

📊 Key Features:

Machine Learning Models: Implementation of various supervised learning algorithms, including Naive Bayes, Decision Trees, Support Vector Machines, and k-Nearest Neighbors, to evaluate and predict customer churn.
Evaluation Metrics: Robust assessment metrics such as accuracy, precision, and recall to gauge the performance of each model and identify the most effective approach.
Data Visualization: Engaging visualizations to illustrate key patterns and factors influencing credit card churn, aiding in a deeper understanding of the predictive models.
💡 Objective:
Our primary goal is to leverage machine learning to forecast credit card churn, providing financial institutions and businesses with actionable insights to enhance customer retention strategies. Explore, experiment, and contribute to the evolving field of predictive analytics.


🛠️ Technologies Used:

Python: Leveraging the power of Pandas, NumPy, and Scikit-Learn. Jupyter Notebooks: Transparent and interactive documentation of the entire workflow.

📈 Results:

Naive Bayes Classifier:

The findings reveal that the Multinomial Naive Bayes model achieved an overall accuracy of 84%, with a precision rate of 86% for correctly predicting stroke cases. Notably, the classifier demonstrated a high recall of 97%, indicating its effectiveness in correctly identifying the majority of stroke patients when they are present.

KNN Classifier:

The findings indicate that the K-Nearest Neighbors (KNN) model achieved an impressive overall accuracy of 95%. Notably, the precision rate for predicting stroke cases is 100%, signifying that when the model predicts a patient to have a stroke, it is correct 100% of the time. Furthermore, the recall is 95%, demonstrating the model's ability to correctly identify 95% of all actual stroke patients, making it a robust classifier for stroke prediction.

Decision Tree:

The findings reveal that the Decision Tree model achieved an accuracy of 91%. Notably, the precision for predicting stroke cases is 95%, indicating that when the model predicts a patient to have a stroke, it is correct 95% of the time. Additionally, the recall is 95%, demonstrating the model's effectiveness in correctly identifying 95% of all actual stroke patients. Overall, these results signify the robust performance of the Decision Tree classifier in stroke prediction.

Random Forest:

The findings indicate that the Random Forest model achieved a high accuracy of 95%. Specifically, the precision for predicting stroke cases is 100%, highlighting that when the model predicts a patient to have a stroke, it is correct 100% of the time. Moreover, the recall is 95%, demonstrating the model's efficacy in correctly identifying 95% of all actual stroke patients. These results underscore the robust and accurate performance of the Random Forest classifier in stroke prediction.

Overall:

K-Nearest Neighbors and Random Forest demonstrated strong performance, achieving an accuracy score of 95%. The Decision Tree followed closely with an accuracy of 91%, while Naïve Bayes yielded the lowest accuracy among the four classifiers, registering at 84%. The analysis reveals that both K-Nearest Neighbors (K-NN) and Random Forest achieved high accuracy scores, with Random Forest emerging as the preferable choice due to its faster computation time and superior handling of overfitting. However, if minimizing computation time is crucial, Naïve Bayes and the Decision Tree classifier present more efficient alternatives. Further investigation could delve into the reasons why a significant number of patients who experienced a stroke did not have heart disease, questioning the reliability of heart disease as an indicator for strokes. The collected data holds valuable insights for identifying critical features such as years of smoking and the presence of hypertension when dealing with patients at risk of stroke. This information can benefit hospitals and drug companies in developing targeted preventive measures based on gender, age, BMI, and other factors highlighted in the exploratory data analysis (EDA) findings.

🔗 Connect with Me:

LinkedIn: [Your LinkedIn Profile] Twitter: [@YourTwitterHandle] Portfolio: [Your Portfolio Website]

🌐 Explore the Project: Feel free to explore the code, datasets, and documentation. Contributions and feedback are highly appreciated!


















## Credit Card Churn Prediction:

  Objective: To employ supervised learning models in Python to assess and predict the likelihood of a credit card customer either staying or churning while also comparing these models to determine the best performance based in metrics such as accuracy, precision, and recall.
  
  Skills Demonstrated: 
      Data Cleaning/Preprocessing: Checks for missing and duplicate values, removal of irrelevant columns/rowa, label encoding of binary categorical features, and the creation of dummy variables for non-binary categorical features to ensure optimal quality for predictive modeling.     
      EDA: Generating correlation graphs/maps, pie charts, histograms, and plots to explore and visualize the relationships between the features in the dataset.
      Machine learning: Implemented Naive Bayes, Decision Tree, SVM, and KNN algorithms to carry out predictions. Overall model accurscy, precison, and recall metrics were calculated to evaluate the effectiveness of each algorithm in prredicting whether a credit card customer would churn.
      Data Visualization: Utilized a confusion matrix for all algorithms used in order to provide a detailed breakdown of true positives, true negatives, false positives, and false negatives. These offered valuable insight into each model's performsnce and aided in the assessment of predictive accuracy.
