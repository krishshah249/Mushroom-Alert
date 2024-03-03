# Mushroom Edible - Poison Classification

This project focuses on classifying mushrooms into poisonous or edible categories using machine learning techniques. The goal is to develop a predictive model that accurately identifies whether a mushroom is poisonous based on its characteristics.

## Overview

Mushroom poisoning is a serious concern, and accurate classification of mushrooms can help prevent accidental ingestion of poisonous species. This project utilizes machine learning algorithms to analyze mushroom features and predict their toxicity level. The dataset used for training and evaluation contains various attributes of mushrooms, such as cap shape, cap color, odor, and more.

## Dataset

The dataset used in this project is the Mushroom dataset from the UCI Machine Learning Repository. It contains information about different mushroom species, including their classification as either poisonous or edible. The dataset is available in the Dataset folder.

## Classification methods used:

- **Decision Tree Classifier**
- **Logistic Regression Classifier**
- **Support Vector Machine Classifier**
- **Random Forest Classifier**

## Exploratory Data Analysis and Data Visualization

#### The distribution of data in various features in the dataset can be understood from the following visualization.

![features][0]

#### The Bar chart below shows the number of mushrooms which are edible or poisonous based on cap-color.

![edible_cap][1]

#### The Bar chart below shows the number of mushrooms which are edible or poisonous based on odor.

![edible_odor][2]

#### The Bar chart below shows the corelation matrix for all the features in the dataset.

![corelation][3]

#### The Bar chart below shows the feature importance using the Random Forest.

![feature_importance][4]

## Model Evaluation and Performance

The classification model is evaluated based on various performance metrics such as accuracy, precision, recall, and F1-score. The evaluation results are presented in the notebook/script and can help assess the model's effectiveness in classifying mushrooms.

#### Visualising the Logistic Regression Training set results

![LogisticRegression_training][5]

#### Visualising the Logistic Regression Test set results

![LogisticRegression_test][6]

#### Visualising the SVC Training set results

![SVC_training][7]

#### Visualising the SVC Test set results

![SVC_test][8]

#### Visualising the Decision Tree Training set results

![DT_training][9]

#### Visualising the Decision Tree Test set results

![DT_test][10]

#### Visualising the Random Forest Training set results

![RandomForest_training][11]

#### Visualising the Random Forest Test set results

![RandomForest_test][12]

#### The best performing model is Random Forest and we can visualize its performance and comparison with other models through ROC-AUC shown below

![ROC_AUC][13]

#### The confusion matrix for the best performing model Random Forest is visualized below

![RF_confusion][14]

## Contributing

Contributions to this project are welcome! If you have ideas for improvements, new features, or bug fixes, feel free to open an issue or submit a pull request.



[0]: images/features.png
[1]: images/edible_cap.png
[2]: images/edible_odor.png
[3]: images/corelation.png
[4]: images/feature_importance.png
[5]: images/LogisticRegression_training.png
[6]: images/LogisticRegression_test.png
[7]: images/SVC_training.png
[8]: images/SVC_test.png
[9]: images/DT_training.png
[10]: images/DT_test.png
[11]: images/RandomForest_training.png
[12]: images/RandomForest_test.png
[13]: images/ROC_AUC.png
[14]: images/RF_confusion.png
