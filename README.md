# Fruit classification using Machine Learning
In this project I use different models and hyperparameters to classify fruits types and compare the results of each approach.

## Description

Structure:
Each branch focuses on a specific model or approah to the problem.

- `main` branch of this project contains the results.
- `using-Logistic-Regression` branch: I solve the problem using Logistic Regression.
- `using-LR-with-a-Neural-Network` branch: I used Logistic Regression using a Neural Network architecture that I build from scratch.
- `using-KNeighborsClassifier` branch: I used sklearn's KNeighborsClassifier both with normalized input data and unnormalized input data.

The results are organized into two groups: 
* binary classification results and
* multiclass classification results.

The binary classification problem is, to classify the fruits into the class label `orange` or `not orange`. For this problem I used a Logistic Regression model using sklearn and a Logistic Regression model using a Neural Network architecture that I build from scracth.

The multiclass classfication problem is, to classify each of the 4 fruit class labels: apple, orange, lemon and mandarin. For this problem I used a KNN classifier where I tried two different approaches: train with unnormalized data, and train with normalized data.

The following sections describe the models used, and the results of each model (branch). If you want to see the code for each model more closely, you can find the code for each model in their respective branches.

## Models used:
* K-Neighbor classifier
* Logistic Regression
* Logistic Regression using a Neural Network

## Binary Classification results:

<table>
  <th>
    <td>Logistic Regression</td>
    <td>Logistic Regression with<br>a Neural Network</td>
  </th>
  <tr>
    <td>Traning score</td>
    <td>77%</td>
    <td>77%</td>
  </tr>
  <tr>
    <td>Testing score</td>
    <td>53%</td>
    <td>53%</td>
  </tr>
</table>

## Multiclass classification results:

<table>
  <th>
    <td>K-Nearest Neighbors with<br>unnormalized data</td>
    <td>K-Nearest Neighbors with<br>normalized data</td>
  </th>
  <tr>
    <td>Traning score</td>
    <td>80%</td>
    <td>95%</td>
  </tr>
  <tr>
    <td>Testing score</td>
    <td>53%</td>
    <td>100%</td>
  </tr>
</table>
