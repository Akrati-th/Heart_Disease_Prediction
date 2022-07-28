# Heart Disease Prediction Project

This project is an attempt to apply **Data Analysis** and **Data Science Algorithms** on the provided data. This project helps in finding the major notions behind the Heart Diseases purely from the perspective of the data. 

## Dataset

The dataset used in the project is shown below -

![Dataset](https://user-images.githubusercontent.com/78207021/181433126-bd6b3f33-45bc-48bd-be9b-31a8cbfd6ec7.png)

The objective of this project is to create a Model which is capable of predicting the possibility of Heart Disease in a person depending on the Count of the following:
```
age:			age
sex:			1: male, 0: female
cp:			chest pain type, 1: typical angina, 2: atypical angina, 3: non-anginal pain, 4: asymptomatic
trestbps:			resting blood pressure
chol:			 serum cholestoral in mg/dl
fbs:			fasting blood sugar > 120 mg/dl
restecg:			resting electrocardiographic results (values 0,1,2)
thalach:			 maximum heart rate achieved
exang:			exercise induced angina
oldpeak:			oldpeak = ST depression induced by exercise relative to rest
slope:			the slope of the peak exercise ST segment
ca:			number of major vessels (0-3) colored by flourosopy
thal:			thal: 3 = normal; 6 = fixed defect; 7 = reversable defect
```

## Visualisations

Visualizations of the data helped in understanding the role of each attribute in the given Dataset in causing Heart diseases within an individuals.

Some of these visualizations are displayed below - 

<p align = "center">
  <img src = "https://user-images.githubusercontent.com/78207021/181433244-4a763561-896c-4bbb-9a9b-d744dd6308e7.png" alt = "Heatmap">
</p>

![Subplots](https://user-images.githubusercontent.com/78207021/181433258-ca90eb40-fe0e-4cae-bc27-ab38c6586736.png)


## Decision Tree Classifier
Decision Tree is a Supervised Learning technique that can be used for both Classification and Regression problems, but mostly it is preferred for solving Classification problems. It is a Tree-Structured Classifier, where internal nodes represent the features of a dataset, branches represent the decision rules and each leaf node represents the outcome.

In a Decision tree, there are two nodes, which are the Decision Node and Leaf Node. Decision nodes are used to make any decision and have multiple branches, whereas Leaf nodes are the output of those decisions and do not contain any further branches. The decisions or the test are performed on the basis of features of the given Dataset. It is a graphical representation for getting all the possible solutions to a problem/decision based on given conditions. Decision Tree Classifier gives the solution of the decision in either **YES** or **NO**.

![Decision Tree Classifier](https://user-images.githubusercontent.com/78207021/181433161-626fcd50-6302-48a7-91ab-fafb9592ae1b.png)

The above graph obtained through Decision Tree Classifier algorithm, clearly shows that **“cp”** is the most responsible feature for causing Heart diseases. 

## k - nearest Neighbour

KNN algorithm or the K-Nearest Neighbor is one of the simplest classification algorithms. Even with such simplicity, it can give highly competitive results.
KNN can be used for both Classification and Regression predictive problems. However, it is more widely used in classification problems in the industry. To evaluate any technique we generally look at 3 important aspects-
1. Ease to interpret output
2. Calculation time
3. Predictive Power
KNN algorithm fairs across all parameters of considerations. It is commonly used for its easy interpretation and low calculation time.

![K - Nearest Neighbour](https://user-images.githubusercontent.com/78207021/181433188-63166900-5b15-4114-a6eb-d69487272e7e.png)

The above graph contains the K value on the x-axis and the accuracy rate on y-axis. This line graph clearly shows that the accuracy of the Model is maximum at K = 4. Therefore, we will use K = 4 to create an efficient model. 

## Comparison between Algorithms based on their Accuracy

![Comparison](https://user-images.githubusercontent.com/78207021/181433195-11b08057-fca6-462c-83bc-25dcba00ec4d.png)

The above bar plot clearly states that KNN machine algorithm is more efficient in comparison to the Decision Tree Classifier algorithm.
As noticed above, the accuracy score of the Decision Tree Classifier is 78.02197802197803. On the other end, the accuracy score of the KNN machine learning algorithm as calculated above is 84.61538461538461. At last but not the least, we can conclude by saying that the KNN model works much better than the Decision Tree Classifier algorithm in this case. 



