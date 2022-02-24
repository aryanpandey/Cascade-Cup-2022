# Round 2 Hackathon
In this Hackathon we were expected to predict whether or not an order would get cancelled by the rider of a Food Delivery Company.

As for our solution to this round, we implemented an XGBoost model on the dataset with a Stratified K-Fold Cross Validation Strategy.

We tried binning of features to give it a categorical appearance due to their better performance on tree based models, 
Tried out an adverserial validation system since there was a stark difference between the validation and test errors

We also implemented some parallel processing so as to run our code a bit faster since this was a huge dataset.

We also tried implementing SMOTE to handle the class imbalance.

Link to our implementation: [Round 2 Python Notebook](https://github.com/aryanpandey/Cascade-Cup-2022/blob/main/Round-2/Cascade_Cup_TDB.ipynb)
