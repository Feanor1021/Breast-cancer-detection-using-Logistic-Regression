# Breast Cancer Detection Using Logistic Regression

This project explores the use of logistic regression for breast cancer detection using the Breast Cancer Wisconsin (Diagnostic) Dataset.

To train the model, I used a dataset from the "UCI" archive provided by "Dr. Wolberg" in 1992. There are 10 dependent and 1 independent variables in the dataset. We will determine whether the tumor is benign or malignant according to 10 dependent variables. 2 means benign, 4 means malignant.

Attribute Information:

  * Sample code number: id number
  * Clump Thickness: 1 - 10
  * Uniformity of Cell Size: 1 - 10
  * Uniformity of Cell Shape: 1 - 10
  * Marginal Adhesion: 1 - 10
  * Single Epithelial Cell Size: 1 - 10
  * Bare Nuclei: 1 - 10
  * Bland Chromatin: 1 - 10
  * Normal Nucleoli: 1 - 10
  * Mitoses: 1 - 10
  * Class: (2 for benign, 4 for malignant)
  
**More information about the data set is in this link : https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Original%29**

## Installation

To run this project, you will need Python 3.x and the following packages:

- numpy
- pandas
- scikit-learn
- matplotlib
- seaborn

You can install these packages using pip:

    pip install numpy pandas scikit-learn matplotlib seaborn 

## Usage

To run the logistic regression model for breast cancer detection, run the following command:


This will train the logistic regression model on the Breast Cancer Wisconsin (Diagnostic) Dataset, evaluate its performance on a testing set, and output the results.

The `Breast_cancer_detection.ipynb` file contains the code for preprocessing the data, splitting it into training and testing sets, training the logistic regression model, evaluating its performance, and visualizing the data.

## Results

The logistic regression model achieves an accuracy of over 95% in predicting whether a tumor is malignant or benign. Feature selection and regularization techniques are found to be effective in improving the performance of the model. The top 10 features selected by the model are found to be highly correlated with breast cancer diagnosis. Data visualization techniques reveal several interesting patterns and relationships between the various characteristics of the tumors and their malignancy.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
