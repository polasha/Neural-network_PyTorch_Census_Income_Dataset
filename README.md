# Neural-network_PyTorch_Census_Income_Dataset

For these exercises I'll perform a binary classification on the Census Income dataset available from the UC Irvine 

Machine Learning Repository. The goal is to determine if an individual earns more than $50K based on a set of continuous and

categorical variables. 

# Census Income Dataset

For this exercises I used the Census Income dataset available from the UC Irvine Machine Learning Repository.

The full dataset has 48,842 entries. For this exercise I have reduced the number of records, fields and field entries, and have 

removed entries with null values. The file income.csv has 30,000 entries


# WorkFlow>

- Seperate continous, catagorical and label column names

- Convert categorical columns to category dtypes

- Shuffle the dataset

- Set the embedding sizes

- Create an array of categorical values

- Create an array of continuos values

- Convert to tensor

- Create a label tensor

- Create train and test from cats, conts and y

- Define the model class

- Set the random seed

- Create a tabular model instance

- Define the loss and optimization functions

- Train the model

- Plot the cross entropy loss against the epoches

- Evaluate the test set

- Calculate the overall percnt accuaracy

- Feed new data through the trained model
