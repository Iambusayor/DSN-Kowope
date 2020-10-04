# DSN-Kowope
Second Place Solution to the Data Science Nigeria AI bootcamp Qualification Hackathon 

 This repository contains the 2nd place solution for the Bootcamp Qualification hackathon organised by Data Science Nigeria (DSN) on Zindi. (link to hackathon: https://zindi.africa/hackathons/dsn-ai-bootcamp-qualification-hackathon).

## Objective: To develop a predictive model that determines the likelihood of a customer defaulting loan payment.
## Packages: Scikit learn, Pandas, Numpy, Matplotlib, Seaborn, Catboost, Regularized Greedy Forest.
## Evaluation Metric: roc_auc_score
## LeaderBoard score: 0.84535675884723
## Models: I did a blend ensembling on the predicitions from two different variations of a voting classifier run at different seed values. Using seed values 32, 45, and 64. Model algorithms were CatBoost, Regularized Greedy Forest and Random Forests.

  # Kowope Mart
Kowope Mart is a Nigerian-based retail company with a vision to provide quality goods, education and automobile services to its customers at affordable price and reduce if not eradicate charges on card payments and increase customer satisfaction with credit rewards that can be used within the Mall. To achieve this, the company has partnered with DSBank on co-branded credit card with additional functionality such that customers can request for loan, pay for goods even with zero-balance and then pay back within an agreed period of time. This innovative strategy has increased sales for the company. However, there has been recent cases of credit defaults and Kowope Mart will like to have a system that profiles customers who are worthy of the card with minimum if not zero risk of defaulting. You have been employed as a Data Scientist to leverage Machine learning to predict customers who are likely to default or not.
