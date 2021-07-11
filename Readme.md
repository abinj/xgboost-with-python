**XGBoost** is an advanced implementation of _**gradient boosted decision trees**_ designed for speed and performance that is dominative competitive machine learning.

XGBoost algorithm has become the ultimate weapon of many data scientists. It's highly sophisticated algorithm, powerful enough to deal with all sorts of irregularities of data.


Building a model using XGBoost is easy. But improving the model using XGBoost is difficult. To improve the model parameter tuning is must.

Dataset: Pima Indians onset of diabetes dataset

        - 8 input variables
        - 1 output variable
        
Problem: Binary classification problem



XGBoost Advantage:

    - Regularization:
        Standard GBM implementation has no regularization like XGBoost, therefor it also helps to reduce overfitting
        XGBoost is also known as `regularized boosting` technique
    - Parallel processing:
        Blazingly faster as compare to GBM
        Use openMP API for parallel processing
        Supports implementation on Hadoop
    - Hign flexibility:
        Allows custom optimization objectives and evaluation criteria
    - Handling missing values:
    - Tree pruning:
        GBM would stop splitting a node when it encounters a negative loss in the split. Thus it is more of a greedy algorithm.
        XGBoost on the other hands make splits upto the max_depth specified and then start pruning the tree backward and remove splits beyond which there is no positive gain.
    - Built-in cross validation:
        XGBoost allows user to run a cross validation at each iteration of the boosting process.
   
   
XGBoost parameters:

    - General parameters:
    - Booster parameters:
    - Learning Task parameters:
    
        