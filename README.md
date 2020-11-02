Our task is to analize and create models that help us  to dentify if a transaction is fraudulent or not. The data set used comes  from 
Kaggle website [Source](https://www.kaggle.com/mlg-ulb/creditcardfraud/tasks) and the informacion of the dataset is as follows: <br>

The datasets contains transactions made by credit cards in September 2013 by european cardholders.
This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. 
The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions. It contains only numerical input variables which are 
the result of a PCA transformation. Unfortunately, due to confidentiality issues, we cannot provide the original features 
and more background information about the data. Features V1, V2, … V28 are the principal components obtained with PCA, 
the only features which have not been transformed with PCA are 'Time' and 'Amount'. Feature 'Time' contains the seconds elapsed between each transaction 
and the first transaction in the dataset. The feature 'Amount' is the transaction Amount.Feature 'Class' is the response variable and 
it takes value 1 in case of fraud and 0 otherwise.

The first notebook: Credit card fraud1_EDA.ipynb takes deals with the exploratory data analysis and visualizations of our data until we finish with a preprocesed 
data set ready to use.
## OUTLINE
* [Introduction](#Introduction )<br>
* [Project description](#Project-description)<br>
* [Dataset](#Dataset)<br>
* [Exploratory Data Analysis](#Exploratory-Data-Analysis) <br>
* [Data visualization](#Data-visualization)<br>
* [Initial Outliers, preemptive analysis](#Initial-Outliers,-preemptive-analysis)<br>
* [Standardization](#Standardization)<br>


The second notebook: Credit card fraud2_MLmodels.ipynb deals with the models used and the metrics used. If you want to run the file, make sure you have card_df_standard.pkl in your same folder in order to upload the processed dataframe. This file can be created by uncommenting the pickle command in the last line of notebook 1. 
# Outline
*[Validation and training datasets](#Validation-and-training-datasets)<br>
*[Imbalanced data](#Imbalanced-data)<br>
*[Machine Learning models](#Machine-Learning-models)<br> 
*[Metrics](#Metrics)<br>
*[Visualization](#Visualization)<br>
*[Hyperparameters](#Hyperparameters)<br>
*[Influential variables](#Influential-variables)<br>
*[Deep Learning](#Deep-Learning)<br>
*[Conclusions](Conclusions)<br>
