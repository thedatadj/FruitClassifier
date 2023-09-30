# FruitClassifier
In this project I use different models to solve a classification problem of predicting fruit type based on a number of features and compare the results.


## Models used:
* K-Neighbor classifier
* Logistic Regression
* Logistic Regression using a Neural Network

## Binary Classification results

<table>
  <th>
    <td>Logistic Regression</td>
    <td>Logistic Regression with a Neural Network</td>
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

## Multiclass classification results

<table>
  <th>
    <td>K-Nearest Neighbors with unnormalized data</td>
    <td>K-Nearest Neighbors with normalized data</td>
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
