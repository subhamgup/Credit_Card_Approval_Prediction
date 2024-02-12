# Credit Card Approval Prediction


**Project proposal to predict credit card approval**

*"A bank's credit card department is one of the top adopters of data science. A top focus for the bank has always been acquiring new credit card customers. Giving out credit cards without doing proper research or evaluating applicants' creditworthiness is quite risky. The credit card department has been using a data-driven system for credit assessment called Credit Scoring for many years, and the model is known as an application scorecard. A credit card application's cutoff value is determined using the application scorecard, which also aids in estimating the applicant's level of risk. This decision is made based on strategic priority at a given time.*

*Customers must fill out a form, either physically or online, to apply for a credit card. The application data is used to evaluate the applicant's creditworthiness. The decision is made using the application data in addition to the Credit Bureau Score, such as the FICO Score in the US or the CIBIL Score in India, and other internal information on the applicants. Additionally, the banks are rapidly taking a lot of outside data into account to enhance the caliber of credit judgements."*

**Class imbalance is a common issue in credit card approval prediction tasks, and it's not uncommon to have a significantly higher number of instances belonging to one class (e.g., 'good' clients) than the other (e.g., 'bad' clients). The concept of a 'good' or 'bad' client is often defined based on historical data and specific criteria set by financial institutions.**

**While class imbalance is normal in these datasets, it can pose challenges during model training. Models might become biased towards the majority class, leading to suboptimal performance on the minority class. In the context of credit card approval prediction, misclassifying a 'bad' client as 'good' can have more severe consequences than the opposite.**

**To address this issue, we will use techniques like oversampling or using different evaluation metrics that consider both precision and recall. We will also employ advanced algorithms like Random Forest, and Boosting algorithms like XGBoost, which are known for their ability to handle imbalanced datasets better than traditional models like Logistic Regression, Decision Trees and K-Nearest Neighbors (KNN).**

**In summary, while class imbalance is expected in credit card approval datasets, we are aware of its impact on model performance and have employed appropriate strategies to mitigate any potential bias.**


## **Machine Learning Development LifeCycle (MLDLC)**

- Data Collection
- Data Preprocessing
- Explorartory Data Analysis (EDA)
- Handling Missing Values & Outliers
- Feature Engineering
- Model Selection
- Model Traning
- Testing & Optimizing
- Model Evaluation
- Model Interpretation


## **Skills Used:**

- Proficient in Python for end-to-end machine learning pipeline
- Expertise in data handling with Pandas and numerical computing with Numpy
- Advanced data visualization using Matplotlib and Seaborn
- Skilled in Scikit-Learn for machine learning tasks: regression, classification, clustering
- Comprehensive understanding of data science methodologies: data collection, wrangling, visualization, and exploratory data analysis
- Experienced in feature engineering and selection for model optimization
- Proven ability in model evaluation and selection for robust predictive analytics


## **Algorithms Employed:**

Logistic Regression for binary classification
Support Vector Machines (SVM) for robust separation
Decision Tree for hierarchical decision-making
Random Forest for ensemble learning and robustness
K-Nearest Neighbors (K-NN) for similarity-based predictions
XGBoost for gradient boosting and high performance


## **Conclusion:**

- In order to develop a robust credit card approval prediction model, we explored various algorithms and ultimately chose the Random Forest algorithm for its consistent and balanced performance.

- **Random Forest Performance**: The initial Random Forest model demonstrated exceptional results with an accuracy of 95.63%, precision of 95.70%, recall of 95.70%, and an impressive F1-Score of 95.70%. The ROC AUC Score, measuring the area under the curve for the true positive rate vs false positive rate, stood at 95.63%.

- **Hyperparameter Tuning Impact**: Following hyperparameter tuning, the model's performance showed some adjustments. However, it's noteworthy that the original model outperformed the tuned version. The initial model had a precision of 95.70%, recall of 95.70%, and an F1-Score of 95.70%, showcasing its superior balance between precision and recall compared to the tuned version.

- **Overall Significance**: The Random Forest model, in its original configuration, emerges as a potent tool for credit card approval predictions. Its ability to maintain a harmonious trade-off between precision and recall makes it a valuable asset for financial institutions aiming for efficient and accurate decision-making.

- **Strategic Considerations**: Despite the slight adjustments post hyperparameter tuning, the original Random Forest model remains strategically significant. The tuning process, while providing insights, did not surpass the well-balanced performance achieved by the initial configuration.

In conclusion, our Random Forest model, especially in its original state, stands out as an effective solution for credit card approval prediction, demonstrating high accuracy and maintaining a balanced interplay between precision and recall.
