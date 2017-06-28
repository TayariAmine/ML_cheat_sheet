# Random Forest pros and cons

**Pros**

* Accuracy
* Runs efficiently on large data bases
* Handles thousands of input variables without variable deletion
* Gives estimates of what variables are important in the classification
* Generates an internal unbiased estimate of the generalization error as the forest building progresses
* Provides effective methods for estimating missing data
* Maintains accuracy when a large proportion of the data are missing
* Provides methods for balancing error in class population unbalanced data sets
* Generated forests can be saved for future use on other data
* Prototypes are computed that give information about the relation between the variables and the classification.
* Computes proximities between pairs of cases that can be used in clustering, locating outliers, or (by scaling) give interesting views of the data
* Capabilities of the above can be extended to unlabeled data, leading to unsupervised clustering, data views and outlier detection
* Offers an experimental method for detecting variable interactions


**Cons**

* Random forests have been observed to overfit for some datasets with noisy classification/regression tasks.
* Unlike decision trees, the classifications made by random forests are difficult for humans to interpret.
* For data including categorical variables with different number of levels, random forests are biased in favor of those attributes with more levels. Therefore, the variable importance scores from random forest are not reliable for this type of data. Methods such as partial permutations were used to solve the problem.
* If the data contain groups of correlated features of similar relevance for the output, then smaller groups are favored over larger groups.
