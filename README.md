# Machine Learning with Modified Fuchs Model

This is a repository that contains all the code used from the paper [Applying Machine Learning Methods to Laser Acceleration of Protons: Lessons Learned from Synthetic Data](https://arxiv.org/abs/2307.16036). It contains the ML model training jupyter notebooks along with the plotting and analysis notebooks. 

## Data Set Generation
The synthetic modified Fuchs data sets are generated with the following notebook in the *datasets* directory
- Fuchs_Data_Generation_v3.2.ipynb

## Hyperparameter Optimization
The hyperparameters were chosen with `GridSearchCV` and the relevant files are in the *model_tuning* directory

## Training Notebooks

The Training notebooks are 
- Train_SVR.ipynb
- Train_NN.ipynb
- Train_GP.ipynb

found in the *training* directory for the Support Vector Regression, Neural Network, and Gaussian Process Regression respectively. These generate output files in the *results* directory

## Optimization Notebooks

The optimization task from *Section 6* is found in the *optimization* directory. There are file for training the models which output predictions in the *predictions_dfs* folder. These predictions are used for the optimization tasks in `Optimization_Comparison_Models.ipynb` and `Optimization_Fuchs.ipynb`.

## Correspondence

My name is Ronak Desai, you can reach me at `desai.458@osu.edu`




