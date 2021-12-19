# Birth Weight Prediction

In this Jupyter Notebook, I am trying to predict Birth Weight.

## Scoring
As we are facing a classification problem, I decided to evaluate my models by the AUC-score and the confusion matrix. For further explanation, see the markdown cells.

## Important steps
After preparing the data, the first step was building the models. I tried these models on several column combinations to find the best for each model. After doing so, I hypertuned the parameters for the best combination of model and columns. In the end, I compared all the combinations by my scoring method and made a decision on which model to use.

## Used Models
I tried several models for my prediction:
- OLS Regression
- Lasso  Regression
- ARD Regression 
- KNN Regression
