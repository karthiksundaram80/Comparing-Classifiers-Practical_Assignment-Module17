## Comparing-Classifiers-Practical_Assignment-Module17

The goal of this project is to use various classifiers to predict whether the customer will subscribe to a bank term deposit or not. The target variable y would be 'yes' if the customer subscribes, Else the target variable will be 'no' (if the customer doesn't subscribe).

# <b> High-level Data Tasks:</b>
1) <b>Load the dataset</b> into a data frame for analysis
2) Look at <b>each feature's data description</b> to understand <b>its missing values and basic statistics</b>
3) Plot <b>Categorical and Numeric features</b> to understand its distribution
4) <b>Transform </b> numeric features by <b>standardizing</b> them as needed
5) <b>Transform </b>numeric features into numeric data
6) <b>Encode</b> categorical features
7) <b>Reduce the cardinality of features</b> having a large number of unique values 
8) Perform <b>K-Nearest Neighbor </b>, <b>Decision Trees</b>, and <b>Support Vector Machines</b> classification on transformed data with y as the target 
variable

# <b>Data Understanding:</b>
1) <b>Acquire Data </b>: Data has been aquired from <b>UCI Machine Learning Repository </b> at https://archive.ics.uci.edu/dataset/222/bank+marketing
2) <b>Data Description </b>: The dataset contains <b>41188 rows</b> with <b>20 independent variables</b> and <b>one dependent variable</b>. The format of raw data is a <b>.csv</b> file. The <b>target variable</b> of the dataset is the <b>Column "y"</b>
3) <b>Data quality</b> : There are <b>no missing data</b> in any of the columns

# <b>Data Preparation:</b>
1)<b>Data Cleanup </b> :
  a) Column <b>"Day of the week"</b> has <b>no impact on the subscription rate</b>. So this column is <b>dropped</b>
  b) Also, there are <b>duplicate records that were dropped</b>
  c) Majority of the value for the feature <b>"poutcome"</b> doesn't denote <b>success or failure</b> based on the previous marketing campaign. Therefore 
    this column is also <b>dropped</b>.

2)<b>Remove Outliers</b>: Took 95th percentile for age.

# <b>Modelling</b>:
Performed <b>K-Nearest Neighbor </b>, <b>Decision Trees</b>, and <b>Support Vector Machines</b> classification on the dataset

# <b>Results </b>:
Compared the results against a <b>baseline model and a simple logistic regression</b>
