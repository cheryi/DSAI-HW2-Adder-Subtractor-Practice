# DSAI-HW2-Adder-Subtractor-Practice
2nd Assignment for DSAI

# Coding Part
### 1.  Adder (A,B: 3 digits) - Adder.ipynb
### 2.  Subtractor (A-B, A>=B) - Subtractor.ipynb
### 3.  Combine adder and subtractor - Combination.ipynb

# Report Part
##  Analyze the results under different number of digits, training epoch, training size, etc

### 1. different number of digits
####   (training data = 18000, testing data = 60000, loss and accuracy both on testing data, epoch=100)
| digits | loss | accuracy |
|-----|-----|-----|
|3|0.3926|0.8617|
|4|1.1936|0.6612|


### 2. different number of training epoch 
####   (training data = 18000, testing data = 60000, loss and accuracy both on testing data)
| epoch | loss | accuracy |
|-----|-----|-----|
|100|0.3926|0.8617|
|200|0.3922|0.8960|
|300|0.3465|0.9135|

### 3. different number of training size
| batch size | loss | accuracy |
|-----|-----|-----|

##  Can we apply the same training approach for multiplication?

From Multiplier.ipynb, the accuracy of validation stop increase from epoch=70(accuracy~=0.58).
Thus, such training approach may not fit on multiplication task.
