# breast_cancer_detection
Model based on kaggle breast cancer data
Here three different jupyternotebook compares different model at different conditions to find out the best model for the dataset
Random forest is compared at different estimators but stil looses to other two
Then, on train-test split, svm looses to logistic model but for this small dataset, logistic was winning at 15% test size which is not good fit for model like this.

Lastly, in svm, the comparision is done based on different gamma values but still looses to default "linear value"
The final model is purely based on winner of all rounds i.e. default gamma SVM
