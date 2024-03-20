# Step 1 

conda create --prefix ./env python=3.8 
conda activate 

The --prefix option in the conda create command allows you to specify the location where you want to create the new conda environment. By default, conda environments are created in a centralized location determined by your conda installation. However, using --prefix gives you the ability to create the environment in a custom location of your choice.


# California-Housing-Price-Prediction-
In this project, I will be documenting my full experience with developing a machine learning model to predict housing prices.  

# Framing the Problem. 
Firstly, it is important to clearly define the objective. Knowing the objective is important because it will determine how you frame the problem, which algorithms to use, and how much effort you will spend. 

Secondly, it could be helpful to look at the currently solution to the problem if any.  

# Explore the Data Set. 

After figuing out the objective, we can determine what kind of supervision the model will need. 
    Based on the objective, we can conclude that it is a typical supervised learning task. 
    
    The Model would be: 
        - Trained with labeled features 
        - A regression task since you're predicting an outpt 
        - Univariate Regression to predict a single value. 

# Selecting a Performace Measure 

We need to select a performance measure for regression probelms. We are going to use RMSE to get an idea of how much error our system makes with its predictions. 

