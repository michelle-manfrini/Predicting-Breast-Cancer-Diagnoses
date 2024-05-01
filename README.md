# Predicting-Breast-Cancer-Diagnoses

Breast cancer is one of the leading causes of death among women, making it important to begin screening for breast cancer early in order to increase the chances of successful treatments. A robust model can assist medical professionals in identifying cases and reducing breast cancer risk. Our project proposed four breast cancer prediction models based on logistic regression, K-Nearest Neighbors Classifier (KNN), Linear Discriminant Analysis (LDA), and Quadratic Discriminant Analysis (QDA). Results reveal that none of the models significantly outperform the other models. Although KNN seems to be the highest performing model based on all the evaluation metrics including the confusion matrix, it does not have a high tendency to predict one class over the other.

This repository contains:

1. A link to [the data](data) used in the project.
2. A link to [final report](docs) of the project.
3. A link to the [source code](src/breast-cancer-predictive-model.ipynb).


# Table of Contents

* Background
* Related Efforts
* Maintainers
* Contributers
* License

# Background

__Project approach:__
1. Problem definition
2. Data
3. Evaluation
4. Features
5. Modelling
6. Experimentation

### 1. Problem Definition ###

In a statement:

> Based on a model trained on synthetic data, how well can said model predict whether or not a clinical patient have breast cancer? Can the model accurately predict whether an individual has breast cancer based on the provided predictors? Which attributes are significant in distinguishing between healthy and affected individuals? How well does the model perform in terms of accuracy and reliability? How clinically relevant and applicable is the model? Can it be used by healthcare professionals for early-stage breast cancer detection?

### 2. Data ###

The original data came from the Coimbra data of the UCI Machine Learning Repository. https://archive.ics.uci.edu/dataset/451/breast+cancer+coimbra

It will be used alongside a synthetic data found in Kaggle. https://www.kaggle.com/datasets/atom1991/breast-cancer-coimbra

### 3. Evaluation ###

The model will be evaluated on various metrics: accuracy, precision, recall, f1-score, confusion matrix.

### 4. Features ###

A list of important information regarding the features of the data. Create data dictionary Quantitative Attributes:

1. Age (years): Represents the age of individuals in the dataset.
2. BMI (kg/m²): Body Mass Index, a measure of body fat based on weight and height.
3. Glucose (mg/dL): Reflects blood glucose levels, a vital metabolic indicator.
4. Insulin (µU/mL): Indicates insulin levels, a hormone associated with glucose regulation.
5. HOMA: Homeostatic Model Assessment, a method assessing insulin resistance and beta-cell function.
6. Leptin (ng/mL): Represents leptin levels, a hormone involved in appetite and energy balance regulation.
7. Adiponectin (µg/mL): Reflects adiponectin levels, a protein associated with metabolic regulation.
8. Resistin (ng/mL): Indicates resistin levels, a protein implicated in insulin resistance.
9. MCP-1 (pg/dL): Reflects Monocyte Chemoattractant Protein-1 levels, a cytokine involved in inflammation.
10. Labels:
    * 1: Healthy controls
    * 2: Patients with breast cancer

# Related Efforts

* Alfian, G.; Syafrudin, M.; Fahrurrozi, I.; Fitriyani, N.L.; Atmaji, F.T.D.; Widodo, T.; Bahiyah, N.; Benes, F.; Rhee, J. Predicting Breast Cancer from Risk Factors Using SVM and Extra-Trees-Based Feature Selection Method. Computers 2022, 11, 136. https://doi.org/10.3390/computers11090136
* Ghani, M.U.; Alam, T.M.; Jaskani, F.H. Comparison of Classification Models for Early Prediction of Breast Cancer. In Proceedings of the 2019 International Conference on Innovative Computing (ICIC), Lahore, Pakistan, 9–10 November 2019; pp. 1–6.
* Jin Yue, Na Zhao, and Liu Liu. "Prediction and Monitoring Method for Breast Cancer: A Case Study for Data from the University Hospital Centre of Coimbra." Cancer Management and Research, vol. 12, 2020, pp. 1887-1893, DOI: 10.2147/CMAR.S242027.
* Khatun, T.; Utsho, M.M.R.; Islam, M.A.; Zohura, M.F.; Hossen, M.S.; Rimi, R.A.; Anni, S.J. Performance Analysis of Breast Cancer: A Machine Learning Approach. In Proceedings of the 2021 Third International Conference on Inventive Research in Computing Applications (ICIRCA), Coimbatore, India, 2–4 September 2021; pp. 1426–1434.
* Nanglia, S.; Ahmad, M.; Khan, F.A.; Jhanjhi, N. An enhanced Predictive heterogeneous ensemble model for breast cancer prediction. Biomed. Signal Process. Control 2021, 72, 103279.
* Patrício, M., Pereira, J., Crisóstomo, J. et al. Using Resistin, glucose, age and BMI to predict the presence of breast cancer. BMC Cancer 18, 29 (2018). https://doi.org/10.1186/s12885-017-3877-1

# Maintainers

@michelle-manfrini

# Contributors 
This project exists thanks to all the people who contribute: @michelle-manfrini, @TjanMichela

# License

[MIT](LICENSE) (c) Michelle Manfrini



