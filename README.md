# Fruit classification using Machine Learning
In this project I use different models and hyperparameters to classify fruits types and compare the results of each approach.

## Description

Structure:
Each branch focuses on a specific model or approah to the problem.

- `main` branch of this project contains the results.
- `using-Logistic-Regression` branch: I solve the problem using Logistic Regression.
- `using-LR-with-a-Neural-Network` branch: I used Logistic Regression using a Neural Network architecture that I build from scratch.
- `using-KNeighborsClassifier` branch: I used sklearn's KNeighborsClassifier both with normalized input data and unnormalized input data.
- `using-KNN-for-Binary-Classification` branch: I used a KNeighborsClassifier the binary classification version of this problem.

The results are organized into two groups: 
* binary classification results and
* multiclass classification results.

The binary classification problem is, to classify the fruits into the class label `orange` or `not orange`. The multiclass classfication problem is, to classify each of the 4 fruit class labels: apple, orange, lemon and mandarin.

The following sections describe the models used, and the results of each model (branch). You can find the code for each model in their respective branches.

## Models used:
* K-Neighbor classifier
* Logistic Regression
* Logistic Regression using a Neural Network

## Binary Classification results:

<table>
  <th>
    <td>Traning score</td>
    <td>Testing score</td>
  </th>
  <tr>
    <td>Logistic Regression</td>
    <td>77%</td>
    <td>53%</td>
  </tr>
  <tr>
    <td>Logistic Regression with<br>a Neural Network</td>
    <td>77%</td>
    <td>53%</td>
  </tr>
  <tr>
    <td>K-Nearest Neighbors<br>unnormalized</td>
    <td>80%</td>
    <td>53%</td>
  </tr>
  <tr>
    <td>K-Nearest Neighbors<br>normalized</td>
    <td>86%</td>
    <td>67%</td>
  </tr>
</table>

#### Discussion

This data is not linearly separable, that is why the logistic regression models are underfitting, they are too simple for the complexity of the data.

## Multiclass classification results:

<table>
  <th>
    <td>Traning score</td>
    <td>Testing score</td>
  </th>
  <tr>
    <td>K-Nearest Neighbors with<br>unnormalized data</td>
    <td>80%</td>
    <td>53%</td>
  </tr>
  <tr>
    <td>K-Nearest Neighbors with<br>normalized data</td>
    <td>95%</td>
    <td>100%</td>
  </tr>
</table>
