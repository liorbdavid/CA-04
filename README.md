# CA-04
### Intro to ML class- Computer Assignment 04

_Brief description:_ <br> 
Exploring Ensemble Classifier models which developed to predict income class using a dataset containing 7 demographic variables. The models are trained, tested, and evaluated for performance (accuracy and AUC). n_estimator hyperparameter range is tested to find the best model, followed by visualization of line graph for each model with the accuracy scores and AUC scores for the n_estiomator values compared. Evantually there is a comparison between all 4 models- Random Forest, AdaBoost, Gradient Boost, and XGB.

_Code explanation:_<br>
Part 1- Data Source and Content (prepare data for ML)
Part 2- Finding Optimal Value of a key Ensemble Method Hyper-parameter a "draft" one
Part 3- Building a Random Forest Model Testing and Evaluating Performance
Part 4- Building AdaBoost, Gradient Boost, and XGB Testing and Evaluating Performance
Part 5- Compare Performance Between the 4 Ensemble Models
 

_Software:_<br>
* Python 3.x
* pandas
* matplotlib.pyplot
* seaborn
* numpy
* time
* LabelEncoder from sklearn.preprocessing
* DecisionTreeClassifier, plot_tree from sklearn.tree
* pydotplus
* confusion_matrix, accuracy_score, precision_score, recall_score, f1_score, roc_curve, auc from sklearn.metrics
* HandlerLine2D from matplotlib.legend_handler 

_Data set:_<br>
The dataset is obtained from the Census Bureau and represents salaries of people along with seven demographic variables. Target classes- 2 ('>50K' and '<=50k') [labels:1,0]. 48,842 rows. The path for the data source: "https://github.com/ArinB/MSBA-CA-03-Decision-Trees/blob/master/census_data.csv?raw=true".


_Instructions:_<br>
Download the code file and run all in order. The Jupyter Notebook contains the entire code and logic for the decision tree classifier, as well as answers for the questions. Before running the program make sure you download the required package and import the needed libraries.

_Authors:_ <br>
Riley Nickel, Taleen Barake, Lior Ben David
