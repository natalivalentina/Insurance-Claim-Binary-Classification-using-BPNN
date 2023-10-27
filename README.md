# Insurance-Claim-Binary-Classification-using-BPNN

This project presents the code/kernel that is used as a final college project.

The aim of this project is to build a predictive model that can determine whether a claim made by someone can be accepted or rejected (binary classification) using Back Propagation Neural Network (BPNN) architecture.

## About Dataset:
The dataset consists of 9 columns and 1338 rows.
The details of the columns in the dataset are as follows:
1. age: age of policyholder
2. sex: gender of policy holder (female=0, male=1)
3. bmi: Body mass index, providing an understanding of the body, weights that are relatively high or low relative to height, objective index of body weight (kg / m ^ 2) using the ratio of height to weight, ideally 18.5 to 25
4. steps: average walking steps per day of policyholders
5. children: number of children / dependents of policyholders
6. smoker: smoking state of policyholder (non-smoke=0;smoker=1)
7. region: the residential area of policyholders in the US (northeast=0, northwest=1, southeast=2, southwest=3)
8. charges: individual medical costs billed by health insurance
9. insurance claim: yes=1, no=0

## About the project:
The dataset provided has several problems, so data preprocessing is carried out to resolve these problems.
After that, data exploration was carried out and separated the dataset into train, test and validation sets with the conditions: 80 train, 10 validation, 10 test.
Create a baseline architecture with n nodes input layer, 2 hidden layers with 2 x n initial nodes and a final layer with many classes (n, 2 x n, 2 x n, num classes).
Description: n is the number of inputs and num_class is the number of classes. Activation function for each hidden layer uses ReLU.
After that, modify the previous architecture to get better accuracy results.
The final step is to evaluate the performance of the two architectures above on the test set by looking for accuracy, precision, recall and F1-Score values.
