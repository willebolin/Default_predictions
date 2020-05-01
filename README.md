# Predicting and simulating loan defaults and losses using neural networks
Final Project in "Financial Risk Analytics" at Stanford. Predicting default for small business loans backed by the US Small Business Administration (SBA)

In this repository you can find the code for our Neural Network as well as the final paper that goes in to more detail explaning our methodology and findings for this project. 

Because of the size of the dataset, and pre-processing done in R, the results can't be replicted by simply running the code. 

# Introduction
The credit industry enables economic activity and fuels economic growth, and is essential to the modern economy. However, lenders will not want to lend money when they do not understand risk; hence, being able to quantify the chance and loss of default is key for creditors to be willing to make loans. Traditional approaches may have relied on heuristic reasoning, coupled with simpler mathematical models, such as linear regression, to assess such risks. It may, however, be difficult to capture such complex phenomena with simple models, and the computation can often be laborious. The deluge of modern data and the development of machine learning techniques offers new techniques for understanding credit risk.

In this paper, we use two conventional, feed forward, fully connected neural networks to firstly, predict the probability of a loan defaulting in 1 year and 5 year’s time, and secondly, predict the expected loss in the case of default. We will train these neural networks on a data set of 150,000 equipment loans backed by the US Small Business Administration (SBA) between 1990 and 2014. The input to our model will include categorical and numerical features from the data set, such as the state that the borrower of the loan is from and how much was borrowed, as well as features we have added ourselves, such as Housing Price Index data, age of the loan, etc.
