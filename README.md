# Classification-of-volcanic-eruptions
## Talent Digital I
The objective of this project is to develop a predictive model based on Random Forests that allows knowing the type of eruption that a volcano will have based on the vibrations measured by the sensors the days before the volcanic eruption.
The result with the predictions has been uploaded in the same repository in a file called 'predictions' in csv format.
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
