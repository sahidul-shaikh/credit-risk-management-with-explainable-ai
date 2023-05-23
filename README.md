# Problem Statement
The use of machine learning algorithms in credit risk assessment has become increasingly popular in recent years, as it has the potential to improve accuracy and efficiency in lending decisions. However, the lack of transparency and interpretability of these models can lead to concerns about potential biases or errors, particularly in cases where the model decisions have significant impacts on people's lives and livelihoods.

Despite advancements in financial technology, the issue of credit risk remains a major challenge for banks and lending institutions. Traditional methods of credit risk assessment such as credit scoring models are limited in their ability to accurately predict risk. Also, traditional credit risk models are often viewed as "black boxes," making it difficult for decision-makers to understand how and why a certain risk assessment was made. This lack of transparency can lead to mistrust and uncertainty in the risk assessment process. As a result, there is a need for more advanced and reliable credit risk models to minimize the risk of default and improve decision-making processes.

Explainable AI (XAI) is an approach to machine learning that aims to increase transparency and interpretability of models, allowing humans to understand how the model arrived at its decision. In the context of credit risk, XAI can help lenders and borrowers understand why a particular loan was approved or denied, which factors played the most significant role in the decision and identify potential areas for improvement.

The goal of this research is to develop an explainable artificial intelligence (XAI) model for credit risk assessment that leverages the latest advancements in XAI techniques. The proposed model will provide transparent and interpretable insights into the risk assessment process, enabling decision-makers to better understand and justify their risk assessments. The model will be evaluated on its ability to accurately predict credit risk and its transparency and interpretability will be compared with existing models to demonstrate its effectiveness. The research will also investigate the trade-off between model transparency and accuracy and explore the potential benefits and limitations of XAI.

# Experiment Details

An organization wants to predict the possible defaulters for the consumer loans product. They have data about historic customer behavior on earlier credit products such as loan. Hence, for acquiring new customers for providing new credit, the organization wants to predict the riskier customers who are likely to default. We are required to use the training dataset to identify the patterns that predict “potential” defaulters.

# Dataset Link
https://www.kaggle.com/datasets/subhamjain/loan-prediction-based-on-customer-behavior?select=Training+Data.csv

# About Data
- ID: Id of the user(All Unique)
- Income: Income of the user
- Age: Age of the user
- Experience: Professional experience of the user in years
- Profession: Profession of the user
- Married/Single: Whether married or not
- House_Ownership: Owned or rented or neither
- Car_Ownership: Does the person own a car
- STATE: State of residence
- CITY: City of residence
- CURRENT_JOB_YRS: Years of experience in the current job
- CURRENT_HOUSE_YRS: Number of years in the current residence
- Risk_Flag: Defaulted on a loan(Target variable)

# Solution Steps
The solution are broadly divided into below steps. The sub steps are also listed while we approach each step.

- Reading and understanding the data
- Exploratory Data Analysis
- Preparing the data for modelling
- Building the model
- Evaluate the model
- Model Explainability (LIME and SHAP)
