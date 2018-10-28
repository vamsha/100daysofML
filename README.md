# ML

## References: 
![picture alt](http://scikit-learn.org/stable/_static/ml_map.png)

----

### Day 1: KNN ###
* Finding the distance between the test point to all train points, and choose the majority from K nearest neighbour.
* Distance fucntions explained (Euclidean, Manhattan, Minkowski and Hamming): https://www.saedsayad.com/k_nearest_neighbors.htm
* [Source code:] https://www.kaggle.com/vamshavardhanreddy/knn-implementation-using-pandas
	
### Day 2: 
Linear regression
* A linear classifier does classification decision based on the value of a linear combination of the characteristics.
* reference: https://leonardoaraujosantos.gitbooks.io/artificial-inteligence/content/linear_classification.html
* Source code: https://www.kaggle.com/vamshavardhanreddy/linear-regression

Feature Selection
* We mainly use feature selection techinques to get insights about the features and their relative importance with the target variable.The idea is to keep most relevant but not redundant feature for predictive model that can yield optimal accuracy.
* source code: https://www.kaggle.com/vamshavardhanreddy/feature-selection	

### Day 3: 
Decision Trees
* Entropy: 
	* Dictionary meaning of entropy pertaining to data is lack of order or predictability with data; In other words, data with the high disorder can be said to be data with high entropy, and, homogenous (or pure) data can be termed as data with very low entropy. Entropy can, thus, be defined as a measure of impurity of data. Higher the entropy, higher impure the data is.
* Information Gain: 
	* Information gain is the difference between the entropy of a data segment before the split and after the split. The high difference represents high information gain. Higher the difference implies the lower entropy of all data segments resulting from the split. Thus, higher the difference, higher the information gain and better the feature used for the split. Mathematically, the information gain, I, can be represented as following:
	* InfoGain = E(S1) - E(S2)
	* E(S1) represents the entropy of data belonging to the node before split
	* E(S2) represents the weighted summation of the entropy of children nodes; Weights equal to the proportion of data instance falling in specific children node.	
* Cost functions:
	* Regression : Mean squared error
	* Classification : GINI
* concept explanation: https://github.com/vamsha/100daysofML/blob/master/Decision_tree
* Source code: https://www.kaggle.com/vamshavardhanreddy/decision-tree-implementation-using-pandas

