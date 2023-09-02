

 ### Since not all fruits are edible, you'd like to be able to tell whether a given fruit is edible or poisonous based on it's physical attributes
### You have some existing data that you can use for this task.
###  you can use the data to help you identify which fruit can be consumed safely?

# Datasets
## I Have taken 
### Three features:-
# 1) Color (Brown or Red),

# 2)thorne Shape (Tapering  or Enlarging), and

# 3)pungent smell (Yes or No)

# Label
Edible (1 indicating yes or 0 indicating poisonous)

![Alt Text](https://github.com/devatroneoptimus/fruit/blob/main/Screenshot%202023-09-02%20170702.png?raw=true)
# One hot encoded dataset
## For ease of implementation, I have one-hot encoded the features (turned them into 0 or 1 valued features)

![Alt Text](https://github.com/devatroneoptimus/fruit/blob/main/Screenshot%202023-09-02%20173836.png?raw=true)
# So I got training dataset as
## X_train = np.array([[1,1,1],[1,0,1],[1,0,0],[1,0,0],[1,1,1],[0,1,1],[0,0,0],[1,0,1],[0,1,0],[1,0,0]])

## y_train = np.array([1,1,0,0,1,0,0,1,1,0])
