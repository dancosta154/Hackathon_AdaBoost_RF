# Hackathon

#### Overview

Partcipated in a hackathon, where the task was to predict if a person's income was in excess of $50,000 given certain profile information. The hackathon was limited to six hours and I was given a constraint stating that I must include AdaBoost in the model.

---

#### Executive Summary

The initial steps completed were to explore and clean the dataset, which included providing values for both ordinal and nominal columns and dropping unnecessary columns for the modeling stage. Once the data was understandable and usable for the modeling the next step was to transform the data using the Polynomial function which assists with flushing out potential relationships within the data. As the number of features were then substantially larger than what is useful in the modeling stage, a PCA model was fit to identify the most useful features (i.e. those with the greatest variance). At this point, the data was ready to proceed into the modeling stage, where a Random Forest Classifier paired with the Adaboost Classifier was fit. 

---

#### Observations

Fitting the data using this method resulted in a 84.9% accuracy score. Comparing this output to the baseline model of 75.9%, it seemed as though the AdaBoost paired with Random Forest Classifier proved useful.