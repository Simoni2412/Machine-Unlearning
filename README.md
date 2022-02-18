# Machine-Unlearning

Goal: Remove all traces of data from a machine learning system without affecting its performance.

Rather than deletion of a particular dataset from the training process and rebuilding the model from scratch, utilization of an unlearning algorithm to produce a new model without retraining our model from scratch.

1.SISA Training 
  Shared, Isolated, Sliced, and Aggregated Training
  Approach developed by researchers in 2019 that involves segregating data into new multiple sets, which are then processed separately and if needed one data point can be         forgotten so only a part of the model has to be processed.
  
2.Adaptive Machine Unlearning 
  Sequential deletion and iteratively updation.
