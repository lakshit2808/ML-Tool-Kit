# R-Squared 
<img src = 'https://www.gstatic.com/education/formulas2/355397047/en/coefficient_of_determination.svg'/>

- R^2	=	coefficient of determination
- RSS	=	sum of squares of residuals
  <img src='https://www.gstatic.com/education/formulas2/355397047/en/residual_sum_of_squares.svg'/> 
  
  - RSS	=	residual sum of squares
  - y_i	=	i^th value of the variable to be predicted
  - f(x_i)	=	predicted value of y_i
  - n	=	upper limit of summation
- TSS	=	total sum of squares
  <img src='https://www.gstatic.com/education/formulas2/355397047/en/total_sum_of_squares.svg'/>
  
  - TSS	=	total sum of squares
  - {n}	=	number of observations
  - y_{i}	=	value in a sample
  - \bar{y}	=	mean value of a sample


# Adj. R-Squared
<img src='https://miro.medium.com/max/1838/1*UcGHE57Zy0GauuLSgzGXug.png'/>
  
  
# Model Optmization
The hyperparameters are the parameters that are not learnt and that are fixed values inside the model equations. For example, the regularization parameter lambda or the inverse regularization parameter C are hyperparameters. So far we used the default value of these hyperparameters, and we haven't searched for their optimal value so that your model reaches even higher performance. Finding their optimal value is exactly what Parameter Tuning is about.
