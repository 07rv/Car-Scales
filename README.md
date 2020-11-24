# Car-Scales

### 🚜 Predicting the Sale Price of Bulldozers using Machine Learning¶ <br/>
**In this notebook**, we're going to go through an example machine learning project with the goal of predicting the sale price of bulldozers.<br/>
Since we're trying to predict a number, this kind of problem is known as a regression problem.<br/>
The data and evaluation metric we'll be using (root mean square log error or RMSLE) is from the Kaggle Bluebook for Bulldozers competition.<br/>
The techniques used in here have been inspired and adapted from the fast.ai machine learning course.<br/>

### Problem Definition
For this dataset, the problem we're trying to solve, or better, the question we're trying to answer is,<br/>
How well can we predict the future sale price of a bulldozer, given its characteristics previous examples of how much similar bulldozers have been sold for?<br/>

### Data
Looking at the dataset from Kaggle, you can you it's a time series problem. This means there's a time attribute to dataset.<br/>
In this case, it's historical sales data of bulldozers. Including things like, model type, size, sale date and more.<br/>
There are 3 datasets:<br/>
   **Train.csv** - Historical bulldozer sales examples up to 2011 (close to 400,000 examples with 50+ different attributes, including SalePrice which is the target variable).<br/>
   **Valid.csv** - Historical bulldozer sales examples from January 1 2012 to April 30 2012 (close to 12,000 examples with the same attributes as Train.csv).<br/>
   **Test.csv** - Historical bulldozer sales examples from May 1 2012 to November 2012 (close to 12,000 examples but missing the SalePrice attribute, as this
   is what we'll be trying to predict).
