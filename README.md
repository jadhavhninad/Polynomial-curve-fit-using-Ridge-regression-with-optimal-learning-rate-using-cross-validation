Using ridge regression for higher order polynomial cure fit. Optimal learning rate is selected using cross validation

run:
python ridgeReg3.py

Note:
Due to linearity in given data (data is sorted along X-axis), using a 5 fold cv error gives bad lambda value. This can be mitigated by either shuffling the data(though the output will depend how data gets shuffled internally) or using a higher order CV fold.

Using 10-fold CV gives lambda = 0.01 and using 100-fold CV give a value of 0.5(this fit is much smoother and seems to be the ideal value)
