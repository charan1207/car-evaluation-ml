

# Car Evaluation Model

This repository contains code for a machine learning model that evaluates car conditions based on various features such as buying, maintenance, doors, persons, etc.

## Key Findings

- The dataset used for training and testing the model is sourced from UCI [Src link https://archive.ics.uci.edu/dataset/19/car+evaluation].
- Descriptive statistics and visualizations revealed key insights into the distribution of data and relationships between features.

## Model Performance


![image](https://github.com/charan1207/car-evaluation-ml/assets/28255223/748d4703-68a1-4fe3-bdb6-e5b212c771d2)




### Training Performance

- Logistic Regression: Training accuracy of [LR:0.6960926193921853].
- K-Nearest Neighbors: Training accuracy of [KNN:0.9558610709117221].
- Decision Tree: Training accuracy of [CT:1.0].
- Support Vector Classifier: Training accuracy of [SV:0.9370477568740955].

### Testing Performance (Best Model - Decision Tree)

- Decision Tree: Testing accuracy of [DT: 0.9710982658959537].
- Classification Report:Score: 0.5549132947976878
##Report
                 precision    recall  f1-score   support

         acc       0.91      0.96      0.94        77
        good       1.00      0.86      0.92        14
       unacc       0.99      0.98      0.99       242
       vgood       1.00      0.92      0.96        13

    accuracy                           0.97       346
   macro avg       0.98      0.93      0.95       346
weighted avg       0.97      0.97      0.97       346



