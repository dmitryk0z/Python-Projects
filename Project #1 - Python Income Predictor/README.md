# Income Predictor (Completed - 12/12/2020)

Using a dataset (the "Adult Data Set") from the UCI Machine-Learning Repository we can predict based on a number of factors whether or not someone's income will be greater than $50,000.

**The technique:**

The approach is to create a **classifier** - a program that takes a new example record and, based on previous examples, determines which 'class' it belongs to. In this problem we consider attributes of records and separate these into two broad classes, <=50K and >50K.

We begin with a training data set - examples with known solutions. The classifier looks for patterns that indicate classification. These patterns can be applied against new data to predict outcomes. If we already know the outcomes of the test data, we can test the reliability of our model. if it proves reliable we could then use it to classify data with unknown outcomes.

We must train the classifier to establish an internal model of the patterns that distinguish our two classes. Once trained we can apply this against the test data - which has known outcomes. We take our data and split it into two groups - training and test - with most of the data in the training set.

We need to write a program to find the patterns in the training set.

**Process overview:**

1) Create training set from data.
2) Create classifier using training dataset to determine separator values for each attribute.
3) Create test dataset.
4) Use classifier to classify data in the test set while maintaining accuracy score.
