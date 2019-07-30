*explain step-by-step process, why linear regression, ending results*


1. Reading and cleaning the Data
   1. Load into dataframe
   2. Drop unnecessary columns/ NA values
1. Create Train Test Split
   1. X_train, X_test, y_train, y_test
1. Min Max Scaler
   1. Fit X to training data
1. Train the SVM
   1. Assigning a Linear kernel
1. Hyperparameter Tuning
   1. Generate GridSearch
   2. Fit grid to training data
   3. Run training module
1. Report results


I used Linear regression due to the fact that there are only 2 possible values in the tested column, so a simple model to separate the 2 values made sense.


This model was able to be trained to 86.9% accuracy.