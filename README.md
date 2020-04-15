# Configuration
Set parameters in model/config.py. You must set the path of train, dev, test and glove.6B.300d.txt. For other parameters, you can use default values.
# How to run
Run the following three commands in order:
* run build_data.py
* run train.py
* delete results/test/test_pred.txt (evaluate dev and evaluate test use the same function, so delete it before you run evaluate.py)
* run evaluate.py
# Results
The predicted results for test data is saved in results/test/test_pred.txt. Accuracy and F1 score are printed and saved in results/test/log.txt.

