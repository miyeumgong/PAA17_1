# PAA17_1
This repo contains the files for PAA 17.1. 


Business Understanding

In this analysis, I'm working with a bank marketing dataset to predict whether a customer will subscribe to a term deposit, which is a time-bound financial product offered by the bank. I believe this is a common problem in the banking industry where the goal is to maximize the number of customers who subscribe to such deposits. Successfully predicting which customers are likely to subscribe helps the bank to:

	1.	Optimize Marketing Efforts: The bank can prioritize outreach efforts towards customers who are more likely to subscribe, reducing marketing costs and improving the efficiency of campaigns.
	2.	Improve Customer Targeting: By identifying customers with a high likelihood of subscribing, the bank can focus on creating personalized offers, increasing the conversion rates of campaigns.
	3.	Increase Revenue: Subscribing to term deposits brings long-term capital to the bank, which can be reinvested or used to fund other banking operations. A higher subscription rate means more steady cash inflow.
	4.	Reduce Customer Churn: Offering the right products at the right time (such as term deposits) can increase customer loyalty, reduce churn, and improve customer retention by creating deeper relationships with existing clients.

Business Problem Statement

The business problem we aim to solve is:

“How can the bank identify which customers are most likely to subscribe to a term deposit based on previous interactions and customer information?”

By solving this problem, the bank can:

	•	Reduce wasteful marketing spending by only targeting customers likely to convert.
	•	Improve the return on marketing investment (ROMI) by increasing the success rate of campaigns.
	•	Boost customer lifetime value (CLV) by nurturing high-value customers and offering products they are more likely to accept.


Data and Features Used

The dataset contains a variety of features, including:

	•	Demographics: Age, job, marital status, education level, etc.
	•	Financial Details: Account balance, housing loan, and personal loan status.
	•	Campaign Information: How many times the customer was contacted and the duration of the last contact.


Outcomes of KNN, Logistics Regression, Decision Tree, and SVM
	•	K-Nearest Neighbors (KNN):
  	•	Accuracy: 0.8891
  	•	Precision: 0.3099
  	•	Recall: 0.2166
  	•	F1 Score: 0.2564
	•	Logistic Regression:
  	•	Accuracy: 0.8899
  	•	Precision: 0.5900
  	•	Recall: 0.2134
  	•	F1 Score: 0.3134
	•	Decision Tree:
  	•	Accuracy: 0.8720
  	•	Precision: 0.4570
  	•	Recall: 0.4587
  	•	F1 Score: 0.4578
	•	Support Vector Machine (SVM):
  	•	Accuracy: 0.8971
  	•	Precision: 0.6526
  	•	Recall: 0.2703
  	•	F1 Score: 0.3823


Findings
	•	Model Performance Metrics (Accuracy, Precision, Recall, F1): Each classifier (KNN, Logistic Regression, Decision Trees, and SVM) provided metrics that help assess how well the model can generalize predictions to unseen data. For example, an accuracy of ~89% for most models indicates that the model correctly predicted customer behavior in about 9 out of 10 cases.
	•	Feature Importance (Logistic Regression & Decision Trees): The analysis revealed that features like balance, job type, education level, and previous contact were significant in predicting whether a customer would subscribe to a term deposit. This suggests that financially stable, employed individuals who had prior engagement with the bank are more likely to subscribe.
	•	Non-linear Relationships (Decision Trees): The tree model captured more complex relationships between features. For instance, married individuals with higher balances and no personal loan history were identified as a segment more likely to subscribe, demonstrating that certain combinations of features drive subscriptions.
	•	Predictive Power (SVM & KNN): These models captured more complex, high-dimensional patterns in the data, providing greater precision in targeting specific customer segments. However, their predictions were harder to interpret for actionable insights, indicating a trade-off between interpretability and accuracy.
	•	Customer Segmentation: The most significant factors influencing term deposit subscriptions were account balance, job type, and previous marketing contact. The bank should prioritize targeting customers with higher balances and stable jobs for more effective marketing campaigns.
	•	Model Accuracy: Models like Logistic Regression and Decision Trees performed well (~89% accuracy), offering clear insights into key factors influencing customer behavior. KNN and SVM provided more precision but at the cost of interpretability.
	•	Predictive Insights: Customers who are financially stable, have had previous positive engagement with the bank, and work in professional occupations are the most likely to subscribe. This can guide the bank in refining its marketing efforts to focus on these high-value segments.
