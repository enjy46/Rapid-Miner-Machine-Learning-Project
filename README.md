# Rapid-Miner-Machine-Learning-Project
**A university group project using Decision Trees**

## Overview:
The project's aim is to train a machine learning model to effectively classify job postings whether they are real or fake. This is done through several phases such as data understanding, data preparation, data modeling, and data evaluation.

### 1. Data Understanding
**Dataset Attributes:** The dataset contains 17,881 examples with 18 attributes, including one label attribute 'Fraudulent'. 

### 2. Data Handling
**Issues:** The dataset had missing values in several attributes.
- Used the 'Replace Missing Value' operator in RapidMiner.
- This process helped improve the overall accuracy of the data.

**Before Handling missing values:**

![Before handling missing values](https://github.com/enjy46/Rapid-Miner-Machine-Learning-Project/blob/main/Screenshot%20(296).png)
![Before handling missing values](https://github.com/enjy46/Rapid-Miner-Machine-Learning-Project/blob/main/Screenshot%20(297).png)

**After Handling Missing Values:**

![After handling missing values](https://github.com/enjy46/Rapid-Miner-Machine-Learning-Project/blob/main/Screenshot%20(293).png)
![After handling missing values](https://github.com/enjy46/Rapid-Miner-Machine-Learning-Project/blob/main/Screenshot%20(294).png)

### 3. Data Modeling and Evaluation
**Model Used:** Decision Trees
- Decision trees classify data by creating a tree structure where each node represents an attribute, each branch a decision rule, and each leaf node an outcome.
- Process includes splitting the dataset into training (70%) and testing (30%) sets to validate the model.
- The model achieved an accuracy of 95.53%.

#### **Note:** The data looks unbalanced because we down-sampled to only 10,000 rows, which resulted in an extremely high accuracy because the application could not handle more than 10,000 rows.

#### **After Being Trained and Tested:**

![After training and testing](https://github.com/enjy46/Rapid-Miner-Machine-Learning-Project/blob/main/Screenshot%20(205).png)
![After training and testing](https://github.com/enjy46/Rapid-Miner-Machine-Learning-Project/blob/main/Screenshot%20(206).png)
![After training and testing](https://github.com/enjy46/Rapid-Miner-Machine-Learning-Project/blob/main/Screenshot%20(207).png)
