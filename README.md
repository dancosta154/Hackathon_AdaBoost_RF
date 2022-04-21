# Good Fast Cheap

### Overview
#### Team One
- Blago Ugrinov
- Sabrina Starr
- Matt Reed
- Dan Costa

#### Constraint

- Must use AdaBoost
- Your choice of features
- Your choice of samples

---

### Background
#### Initial Assessment

In our initial assessment, we cleaned the data to ensure it was understandable and usable for the modeling we executed. Once basic cleaning was complete, we transformed the data using the Polynomial function to flush out potential relationships within the data. As the number of features were then substantially larger than we wanted to use for our model, we then fit the data to against a PCA model to identify the most useful features (i.e. those with the greatest variance). 

---

### Observations

At this point, our data was in a much better place to proceed into the modeling stage. To best determine those records who's wage was greater than $50,000, we used a Random Forest Classifier paired with the Adaboost Classifier. Fitting the data using this method resulted in a 84.9% accuracy score.