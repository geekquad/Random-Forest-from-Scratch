# Random-Forest-from-Scratch
Random forests is a supervised learning algorithm. It can be used both for classification and regression. It is also the most flexible and easy to use algorithm. A forest is comprised of trees. It is said that the more trees it has, the more robust a forest is. Random forests creates decision trees on randomly selected data samples, gets prediction from each tree and selects the best solution by means of voting. It also provides a pretty good indicator of the feature importance.

## Working of the Algorithm
It works in four steps:
- Select random samples from a given dataset.
- Construct a decision tree for each sample and get a prediction result from each decision tree.
- Perform a vote for each predicted result.
- Select the prediction result with the most votes as the final prediction.
<img src="https://res.cloudinary.com/dyd911kmh/image/upload/f_auto,q_auto:best/v1526467744/voting_dnjweq.jpg">
<hr> </hr>

## Documentation of Random Forest:
<a href="https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestClassifier.html"> https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestClassifier.html </a>
<hr> </hr>

## Parameters of the Algorithm:
<ul>
  <li><b>min_samples_split (default value = 2)</b></li>
  nodes cannot be further seperated below this value. 
  <li><b> criterion : optional (default=”gini”)  </b></li>
  It controls how a Decision Tree decides where to split the data. 
  It is the measure of <b>impurity</b> in a bunch of examples. 
   This parameter allows us to use the different-different attribute selection measure. Supported criteria are “gini” for the Gini index and “entropy” for the information gain.
  <li> <b> n_estimators(default value = 100 </b></li>
  This parameter tells is the number of trees in the forest.
  </ul>
 <hr>   
