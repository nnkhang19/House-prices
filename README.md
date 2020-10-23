# House price problem

## Introduction 
This project is my excersise to practice and improve skill after learning data visualization and linear regression. I tried to apply some statistics, data visualization tools and also a simple linear model in python frameworks.



## Frameworks
* Pandas : loading and preprocessing data <br />
* Numpy :   modifying and computating <br />
* Matplotlib and seaborn : data visualizing <br />
* Scipy and stats: statistics tools <br />
* Sklearn : training and testing.



## Data visualization

### 1. One feature interpretion
#### 1.1 Continous feature
* Each feature is verified separately. 
* Plotting features in boxplot and distplot to determine outliers and visualize the distribution. 
* Skewness and kurtois are also calculated.

![Image1](https://user-images.githubusercontent.com/63390676/96951679-34d90100-1517-11eb-92d8-9be7e48c39e5.png)

#### 1.2 Categorical feature
* Barplot is used to visualize the distribution of each feature.

![I2](https://user-images.githubusercontent.com/63390676/96952439-107e2400-1519-11eb-850f-7e04994f8fbe.png)


### 2 Two features interpretion

#### 2.1 Continous features
* Features are plotted in pairplot to reference the correlation between 2 features in a pair. 
* Spearman method is used to calculate these correlations.

![I3](https://user-images.githubusercontent.com/63390676/96953022-5edff280-151a-11eb-8ee4-675eaef5894c.png)

#### 2.2 Categorical features
* A cross-table is created from each pair of features. 

![I4](https://user-images.githubusercontent.com/63390676/96953272-df9eee80-151a-11eb-9ae8-c69a8dd362db.png)

* There are 2 hypotheses : These features are independent and the variances are homogenous and the p-value is 0.05.

* Chi-squared and anova are used to determined the truth value of 2 hypotheses.

## Preprocessing
* Null values and outliers are removed from the dataset.
* The training dataset is splitted into 2 sets: train and test with the ratio: 4/1.

## Training ann testing
### 1. Training
* Linear Regression model in sklearn library is used for the training task.

### 2. Testing
* A table containing actual and predicted values in the test set. 

![I5](https://user-images.githubusercontent.com/63390676/96954811-61dce200-151e-11eb-843b-5d89144c9a46.png)

* A barplot combining actual and predicted values of the first 25 variables in the set to visualize the differences.

![I6](https://user-images.githubusercontent.com/63390676/96954968-c0a25b80-151e-11eb-97a7-b1bebe88e53b.png)

* MSE is used to determine the difference.





