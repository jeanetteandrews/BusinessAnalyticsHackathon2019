# SFU Beedie Business Analytics Hackathon 2019 <br /> 
### Case Context
How do we predict the rate of churn? For this competition, one Canadian telecom company was struggling with customer loss. Given a [sample](https://github.com/jeanetteandrews/hackathon2019/tree/master/Datasets) of 3,750 customers, my team was tasked to predict the rate of churn of a test set of 1,250 customers, as well as finding the key variables that indicate customer churn. We then presented our conclusion to judges from various businesses in Vancouver. We were given four hours to complete the hackathon. <br />

Please view [Case_Context.pdf](https://github.com/jeanetteandrews/hackathon2019/blob/master/Case_Context.pdf) for full details of the hackathon!

### Process
In order to predict the rate of churn, I used the sample of 3,750 customers to create four different machine learning models in [R](https://github.com/jeanetteandrews/hackathon2019/blob/master/R_Hackathon2019.Rmd): decision tree, random forest, logistic regression, and neural network. I then created a lift chart to compare each of the models' accuracy at the 40% sample proportion level. Our team used the decision tree, which was the most accurate model out of the four, to predict the probability of churn for the 1,250 "holdout" customers, and then submit the data to the leaderboard. 

<table width="500" border="0" cellpadding="0">

<tr>

<td align="center" valign="center">
<img src="https://raw.githubusercontent.com/jeanetteandrews/hackathon2019/master/Graphs/decisionTree.png" />
<br />
Decision Tree
</td>

<td align="center" valign="center">
<img src="https://raw.githubusercontent.com/jeanetteandrews/hackathon2019/master/Graphs/randomForest.png" />
<br />
Random Forest
</td>

<td align="center" valign="center">
<img src="https://raw.githubusercontent.com/jeanetteandrews/hackathon2019/master/Graphs/logisticRegressionREADME.png" />
<br />
Logistic Regression
</td>

<td align="center" valign="center">
<img src="https://raw.githubusercontent.com/jeanetteandrews/hackathon2019/master/Graphs/nueralNetwork.png" />
<br />
Neural Network
</td>

</tr>

</table>

### Results
Compared to the actual churn rates, our model predicted churn with 81.7% accuracy at the 40% level. The variables that were the highest indicators of customer churn were the customer's location, days spent roaming, and total monthly bill.
