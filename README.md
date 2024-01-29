# Assignment-17.1

### Project Summary: Decision Tree Model Outperforms in Bank Marketing Campaign Analysis

#### Overview
In this practical assignment, I conducted an in-depth analysis comparing the performance of four classifiers - k-nearest neighbors (KNN), logistic regression, decision trees, and support vector machines (SVM) - using a dataset from a Portuguese banking institution focused on telephone marketing campaigns for bank products. This dataset was obtained from the UCI Machine Learning Repository.

#### Objective
The primary business objective of this effort is to develop a predictive classifier model that can accurately identify potential customers who are most likely to be converted to a customer from a marketing call. This will improve conversion rates, optimize resource allocation and improve customer interaction by engaging less with less interested customers.

Given the context, that a sales and marketing team will be the group primarily using this model, it should be explainable to people without a data science background. This context creates a preference for a decision tree model so if all models are equal, it should be the winning model.

Fundamentally this model should result in a competitive advantage and increased profits.

#### The Data
The dataset provided over 40 thousand entries with 21 variables which was reduced to just over 30 thousand entries through cleaning. This resulted in a dataset which provided a comprehensive and accurate view of client interactions, campaign details, and customer demographics. 

#### Method and Analysis
This assignment was done using CRISP-DM methodology following the below process:
1. **Business Understanding**: The business and problem was researched to provide context to the assignment, this was aided by my previous experience in finance in Spain, which has a very similar banking industry.
1. **Data Preparation**: The dataset underwent rigorous cleaning and preprocessing to ensure it was suitable for modeling.
2. **Model Training and Evaluation**: Three iterations of four kinds of classication models were evaluated. The models were, logistic regression, KNN, decision tree and SVM. Hyperparameter tuning and cross validation were used. Each model was evaluated using metrics like training time, accuracy and precision. Despite all models showcasing near 90% accuracy, there was room to improve precision by refining them. 
3. **Evaluation - Decision Tree as the Chosen Model**: All models worked well and  the decision tree classifier was selected as the most suitable model. This decision was driven by two key factors:
   - **Interpretability**: A known advantage of decision trees is their ease of explanation to stakeholders. The model's ability to visually represent decision paths and criteria is invaluable, especially when communicating complex analytical findings to individuals without a technical background, like the sales and marketing teams in this example which will be using the model.
   - **Personal Experience**: My familiarity and experience with decision trees played a significant role in effectively utilizing this model to extract meaningful insights from the data.

#### Key Insights and Next Steps
1. **All Models Worked Well**: All models achieved near 90% Accuracy and Precision above 50%. 
2. **Practically, a Decision Tree May Work Best**: Since all models are similarly optimized, the decision tree may be easiest to explain and deploy with outside teams.
3. **Gains May Be Available By Further Exploring A Decision Tree Model**: While accuracy is at nearly 90%, precision is in the 60s and may have room for improvement through further refining. 

#### Submission Note
This comprehensive analysis, encapsulated in a Jupyter Notebook, is available in the provided GitHub repository URL: https://github.com/CuentaVentana/Assignment-17.1. 
