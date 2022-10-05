# Classification-of-volcanic-eruptions
## Talent Digital I
The objective of this project is to develop a predictive model based on Random Forests that allows knowing the type of eruption that a volcano will have based on the vibrations measured by the sensors the days before the volcanic eruption.

The result with the predictions made from testing dataset "jm_X_test.csv" has been uploaded in the same repository in a file called 'predictions' in csv format.

This exercise corresponds to a challenge conducted online at https://nuwe.io in Data Science category and the objective is to maximize 'f1-score' (macro) metric.
## Dataset explanation
The dataset has 2,100 instances, 6 features and a target.
- **Features**: It contains 6 features in 6 columns, which are the measured vibrations of the different sensors the days before the volcanic eruption
- **Target**: The target corresponds to the label that classifies the types of eruptions, according to the features measured by the sensors.
    - Target 0 corresponds to a type eruption Pliniana
    - Target 1 corresponds to a type eruption Peleana
    - Target 2 corresponds to a type eruption Vulcaniana
    - Target 3 corresponds to a type eruption Hawaiana
    - Target 4 corresponds to a type eruption Estromboliana
## Results
We have use a RandomForest model for our prediction. Applying cross validation we have verified that the model remains stable and that there was no overfitting. Through GridSearch we have adjusted the hyperparameters improving the initial model. The final F1_Score obtained is 0.775
## Requeriments
This notebook requires a Python 3.6 or newer version.

## Repository files
The repository contains the following files:
- Volcan_prediction.ipynb: Python notebook with the code of the project
- jm_train.csv: Dataset for train the model
- jm_X_test.csv: Dataset to test the model
- predictions.csv: File with the results of the model for the test_X_test.csv

## Requeriments
To run this notebook you must have installed the following libraries:
 pip install pandas     
 pip install numpy     
 pip install matplotlib     
 pip install seaborn     
 pip install scipy     
 pip install -U scikit-learn
## Acknowledgements
For the preparation of this exercise, different online resources have been consulted:

https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestClassifier.html

https://towardsdatascience.com/hyperparameter-tuning-the-random-forest-in-python-using-scikit-learn-28d2aa77dd74

https://towardsdatascience.com/random-forest-hyperparameters-and-how-to-fine-tune-them-17aee785ee0d

https://www.analyticsvidhya.com/blog/2020/06/auc-roc-curve-machine-learning/

