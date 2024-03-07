# Predicting Glaucoma and Heart Diagnoses using Optimal Sparse Regression Trees

## Introduction
In recent years, the widespread adoption of machine learning algorithms has brought significant advancements across various industries. However, in fields like healthcare and forensics, where decisions directly impact human lives, the opacity of these "black box" models raises concerns about interpretability and accountability. To address this, researchers have developed interpretable models like the Optimal Sparse Regression Tree (OSRT), offering transparency and explainability without compromising accuracy.

## Problem Statement
This project aims to leverage the OSRT algorithm to predict the likelihood of glaucoma in patients before symptoms manifest. Early detection of glaucoma is critical for timely intervention and improved patient outcomes. By developing an interpretable model, we seek to enhance the trust and confidence of stakeholders in AI applications within the healthcare domain.

## Literature Review
Various studies underscore the need for interpretable AI models, particularly in healthcare. Existing AI models demonstrate the feasibility of glaucoma detection, while researchers emphasize the importance of understanding AI predictions. The OSRT algorithm presents a promising solution, offering both accuracy and interpretability.

## Data Plan
The dataset comprises Medicaid claims related to eye health conditions, providing demographic information about patients. Features include patient demographics, visit details, and diagnostic outcomes. Preprocessing involves handling missing values and encoding categorical variables. Exploratory Data Analysis (EDA) will uncover insights to guide model development.

## Feature Selection/Analysis
Selected features include patient demographics, visit details, and diagnostic outcomes. Encoding categorical variables enables model analysis. EDA techniques such as correlation matrix visualization and dot plots will reveal underlying patterns. K-fold cross-validation ensures robust model evaluation.

## Modeling Plan
The OSRT algorithm serves as the primary model, complemented by benchmark models like XGBoost, Random Forest Regressor, SVM,  and CART. Evaluation metrics include mean square error, number of leaves, depth, and R square. Model performance will be assessed comprehensively to identify strengths and weaknesses.


## References
Centers for Disease Control and Prevention. (2023). Medicaid Claims (MAX) - Vision and Eye Health Surveillance.
Chen, X., Xu, Y., Wing Kee Wong, D., Yin Wong, T., & Liu, J. (2015). Glaucoma detection based on deep convolutional neural network.
Garrett, B. L., & Rudin, C. (2023). Interpretable Algorithm Forensics.
Ghosh, A., & Kandasamy, D. (2020). Interpretable Artificial Intelligence: Why and When.
Hod, D. (2023). Explainable AI: The Importance Of Adding Interpretability Into Machine Learning.
Miotto, R., Li, L., Kidd, B. A., & Dudley, J. T. (2016). Deep Patient: An Unsupervised Representation to Predict the Future of Patients from the Electronic Health Records.
Samek, W., Wiegand, T., & Muller, K.-R. (2017). Explainable Artificial Intelligence: Understanding, Visualizing and Interpreting Deep Learning Models.
Zhang, R., Xin, R., Seltzer, M., & Rudin, C. (2023). Optimal Sparse Regression Trees.
Author Credits

## This project proposal is based on research by Cynthia Rudin, Brandon L. Garrett, and other researchers as cited in the references section. Their contributions to interpretable AI and healthcare informatics have been instrumental in shaping this project.
