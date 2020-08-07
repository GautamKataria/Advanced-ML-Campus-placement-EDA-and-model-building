# Campus-placement-EDA-and-model-building

## Motive:
Campus placements are a very important thing for every student persuing a degree.
One day i stumbled upon a dataset of campus placements for MBA students
So i took it as an opportunity to learn more about placements.

Link to Kaggle dataset: [Here](https://www.kaggle.com/benroshan/factors-affecting-campus-placement)

## Working
##### The jupyter notebook has the complete Exploratory data analysis done on this dataset from which i was able to gather many interesting observations.

##### Further i cleaned up the data and preprocessed it to train a Machine learning model on it

##### I created 3 models, [Logistic regression , Random forrest classifier(with hyperparameter tuning) , Decision tree classifier(with hyperparameter tuning)] and got accuracies of 84.6%,80% and 86% respectively.

##### So i went ahead and chose the best 2 performers to make a voting classifier.
##### The ensemble voting classifier gave us an accuracy of 90.77% with great precision,recall and f1 scores, hence we save the given model.
