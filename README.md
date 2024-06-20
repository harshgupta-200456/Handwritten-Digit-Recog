Made a handwritten Digit Recognition system using neural networks.
MNIST data set was used
Data set was divided into 3 parts 1.training dataset 2.testing dataset 3.crossvalidation dataset
Data was normalized using mean normalization
flattened the data to a single dimensional array
used 3 different layers 1.using 120 units and relu activation 2. using 40 units and relu activation 3. using 10 units and linear activation
we use sparseCategoricalCrossEntropy(from_logits=true.) loss function 
from_logits = true is used for more numerical stability
Different values of regularization parameters was tried to mainatin a balance between high bias and high variance
