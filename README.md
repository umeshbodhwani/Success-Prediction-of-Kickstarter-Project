# Kickstarter-Project-Success-Prediction
Predicting the success of projects on Kickstarter

# Notebooks

1. Get_Data.ipynb <- Used to get data for the project 
	- The code to save final df has been commented as we used last three months data at the time
	of building the model. Using it again would lead to change in data and thereby change the analysis
	- Data are in the zip file

2. Clean_Data.ipynb <- Notebook to clean data and save cleaned data in data directory
3. EDA.ipynb <- Notebook used for performing the Exploratory analysis (univariate, bivariate, multivariate) to understand data
4. sensitivity_analysis.ipynb <- Notebook used for building the models on the "US" datasets
5. Category_*.ipynb <- Notebooks used for carrying forward the analysis for the top 5 categories for the "US" data
6. State_*.ipynb <- Notebooks used for carrying forward the analysis for the top 3 states for the "US" data
7. neural_network_1.ipynb <- Notebook used to build a 5 hidden layer feedforward neural network (Written using tensorflow 1.9.0)
		- Reference to setup Tensorflow environment using conda: https://towardsdatascience.com/tensorflow-gpu-installation-made-easy-use-conda-instead-of-pip-52e5249374bc

		- To create tf_gpu environment execute: conda create --name tf_gpu tensorflow-gpu==1.9.0

		- When executing the notebook make sure that the notebook is running in the correct environment

		- please make sure that pandas and numpy are installed in tf_gpu environment too

		- Do not forget to set the correct log path in the notebook


