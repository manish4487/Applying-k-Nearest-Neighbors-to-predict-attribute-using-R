# Applying-k-Nearest-Neighbors-to-predict-attribute-using-R

1. Download the dataset Auto.csv and explore the overall structure of the dataset using str(). 

2. Convert the attribute horsepower from character to integer. The horsepower attribute has some missing values. 
   Remove the observations   with missing values.Delete the rows with missing values from the data frame. 
   
3. Explore the data in order to investigate the association between mpg and the other features. 
   Which of the other features seem most likely to be useful in predicting mpg using scatterplot.   

4. Create a new attribute mpg1 that contains 1 if mpg is strictly greater than its median, and 0 if mpg is equal or less than its median.
   Decide which attributes you are going to use to predict mpg1. Remove all remaining attributes, including mpg. 

5. Set the seed of the random number generator to a fixed integer, say 1. So that you can reproduce your work: > set.seed(1) 
   Normalize the attribute values and Randomize the order of the rows in the dataset 

6. Split the data into a training set and a test set. Use a test set of 100 rows. 

7. Perform kNN on the training data, with several values of K, in order to predict mpg1. What test errors do you obtain? 
   Which value of K seems to perform the best on this data set?
