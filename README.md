# classification-diabetic

Label patients as diabetic/non diabetic
One such function is a logistic function, which forms a sigmoidal (S-shaped) curve, like this:


1. Exploratory analysis:

- Box plots to visualize the relationship between the features and the predicted

2. Test train split

3. Model Logistic

4. Predict and accuracy
    - accuracy
    - confusion matrix
        - The model predicted 0 and the actual label is 0 (true negatives; top left)
        - The model predicted 1 and the actual label is 1 (true positives; bottom right)
        - The model predicted 0 and the actual label is 1 (false negatives; bottom left)
        - The model predicted 1 and the actual label is 0 (false positives; top right)
        - Accuracy: (TP+TN)/(TP+TN+FP+FN) - out all of the predictions, how many were correct?
        - Recall: TP/(TP+FN) - of all the cases that are positive, how many did the model identify?
        - Precision: TP/(TP+FP) - of all the cases that the model predicted to be positive, how many actually are positive?
        - classification report
    - received operator characteristic (ROC) chart
        -  true positive rate (which is another name for recall) and the false positive rate

5. Pipelining preprocessong

- new features by transfornmations or combinations - feature engineering
- normalizing numeric and encoding categorical as numeric indicators

Note:

Using Multiclass classification models


