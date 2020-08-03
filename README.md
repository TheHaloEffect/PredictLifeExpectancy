# Description
A Multivariable Regression model that predicts life expectancy given other variables. Used a Kaggle dataset that has data on many countries, regarding GDP, population, infant/adult mortality, life expectancy etc. It was an attempt to try out the machine learning knowledge that I have been teaching myself. Some variables seemed to have very high P-Values so I removed some from the model and compared the BIC and R-Squared values to the original full model and got a better BIC result with a very slightly lower R-Squared value.

# BIC and R-Squared
For original full model

BIC: 7204.271948131657
R-Squared: 0.8375967031163584

For reduced model:

BIC: 7164.046187986783
R-Squared: 0.8372414639834214


# Screenshots
<h3>P-Values</h3>
<img src="pvalues.png" alt="pvalues list" width="200" height="400">

<h3>Actual vs Predicted Life Expectancy</h3>
<img src="scatterplot.png" alt="Life Expectancy Graph" width="200" height="400">
 
<h3>Actual and Predicted Values</h3>
<img src="values.png" alt="Actual and Predicted Values" width="200" height="400">

