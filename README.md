# Evaluation-of-SVM-Kernels-on-Diabetes-Data
Evaluation of the Support Vector Machine (SVM) Model with Various Kernels: Accuracy, Recall, and Precision
# Evaluation of SVM Kernels on Diabetes Data

This project evaluates the performance of various Support Vector Machine (SVM) kernels on diabetes data.

## Steps to Run the Code

1. **Import Libraries:**
   - numpy
   - pandas
   - StandardScaler from sklearn
   - train_test_split from sklearn
   - svm from sklearn
   - accuracy_score, recall_score, precision_score from sklearn

2. **Read Data from Google Drive:**
   - Using pandas to read the CSV file

3. **Prepare Data:**
   - Separate the target variable (Outcome) from feature data

4. **Standardize Data:**
   - Use StandardScaler to standardize the data

5. **Split Data into Training and Test Sets:**
   - Use train_test_split to divide the data

6. **Train SVM Model:**
   - Build and train the SVM model with the rbf kernel

7. **Predict and Evaluate Model:**
   - Predict and evaluate the accuracy, recall, and precision of the model

8. **Test Different Kernels:**
   - Evaluate the accuracy of different kernels including linear, poly, rbf, and sigmoid

## Outputs

- Model accuracy on training and test data
- Recall and precision of the model on test data
- Comparison of different SVM kernels

## How to Run

1. Copy the code into your Python environment.
2. Upload your data in CSV format to Google Drive and add the link to the code.
3. Run the code and analyze the results.

## Data Visualization

Here is a bar chart showing the distribution of diabetes outcomes in the dataset:

![Diabetes Outcome Distribution](sandbox:/mnt/data/diabetes_outcome_distribution.png)

## Dataset

You can download the diabetes dataset used in this project from [this link](https://drive.google.com/uc?id=1gSbDCCFzBuIQv0TihYC927MVLWmyrvfZ).

## Author

- [maryam-hekmat]
