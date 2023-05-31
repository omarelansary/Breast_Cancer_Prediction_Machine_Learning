# Breast_Cancer_Prediction_Machine_Learning
Machine Learning Based for Breast Cancer Prediction

The project focuses on extracting data from breast mammograms and applying four different models: Decision Tree, Random Forest, k-Nearest Neighbors (k-NN), and Logistic Regression.

To ensure data quality, I implemented data handling techniques such as removing missing values and checking cardinalities and outliers. Additionally, I conducted analytical exploration of the data to gain insights and identify patterns.

Briefly, the project consists of the following steps:

Data Extraction: Extracting relevant data from breast mammograms.
Model Selection: Employing four machine learning models - Decision Tree, Random Forest, k-NN, and Logistic Regression - to train and test the data.
Data Handling: Removing missing values and examining cardinalities and outliers in the dataset.
Analytics: Conducting exploratory data analysis to uncover patterns and gain insights.

In addition to the steps mentioned earlier, I evaluated the performance of each machine learning model using Receiver Operating Characteristic (ROC) analysis and Area Under the Curve (AUC) metrics.

ROC analysis helps assess the performance of a binary classification model by plotting the True Positive Rate (TPR) against the False Positive Rate (FPR) at various threshold settings. It provides insights into the trade-off between sensitivity and specificity.

AUC, or the Area Under the ROC Curve, quantifies the overall performance of a classifier. It represents the probability that a randomly selected positive instance will be ranked higher than a randomly selected negative instance. Higher AUC values indicate better model performance.

By applying ROC analysis and calculating AUC for each of the employed models (Decision Tree, Random Forest, k-NN, and Logistic Regression), I was able to compare and assess their predictive capabilities. This evaluation process allowed me to determine which model performed best in terms of distinguishing between benign and malignant tumors based on the given dataset.

In summary, I evaluated each model's performance using ROC analysis and AUC metrics, which provided a quantitative assessment of their predictive accuracy in classifying breast tumors as benign or malignant.

Overall, the purpose of this project is to leverage machine learning algorithms to predict the nature of breast tumors (benign or malignant) based on the extracted data from mammograms.
