# Classifying Gestures From Muscle Activity
### Overview
Use data from the myo armband, an array of 8 muscle sensors worn on the arm, to classify 4 different hand gestures.

Data source: https://www.kaggle.com/kyr7plus/emg-4

### Data Overview

- (8 sensors)*8 measurements = 64 columns
- Approximately 2,900 observations of each of the 4 classes
- 11677 total observations


### Models Evaluated
Since this was an early project for my data science course at Thinkful, I didn't attempt to use any neural network or deep learning models sine they were not covered in my classes yet.

- Logistic Regression
- KNN
- Random Forest
- Support Vector Machine
- AdaBoost Classifier
- Gradient Boosting Classifier
- XGBoost

### Results
- Achieved over 96% test accuracy using the XGBoost model

### Questions going forward

- Can this type of model work with a larger number of classes?
- Does this model work with different users?
- Can we get the same results with fewer sensors?
