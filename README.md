# Model used to sort importance value for `MantiCore` 

Rankings.io applied a state-of-the-art machine learning model to determine the importance of SEO factors on rankings. This process is more advanced than a simple correlation measure like a Spearman correlation. The statistical method of choice for Rankings MantiCore is the Machine-learned ranking (MLR) model, also called Learning to rank.  


The MLR is a widely used machine learning technique in the field of information retrieval for natural language processing and data mining. For instance, search engines have been using learning to rank for almost two decades now. In a learning to rank problem, there is an ordered list of items and the goal for the model is to calculate a score for each item based on the dependent variables (in our case, the Organic Google Rank).  


In the process of building the model, the data set was split into two pieces: the training data set (containing around 70% of searches) and testing data set (the remainder with about 30%). The MLR model was fitted using training data, predictions were calculated for the test data set. The predictions were compared to real observed rankings.  


Then, we provided a deep dive into single variables that the model identified as particularly important to impact organic Google Rank positions.  

The model used to sort the variable importance can be found in the notebook `model.ipynb`. 
