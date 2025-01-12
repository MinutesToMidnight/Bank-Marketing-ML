Currently modules are designed for multiclassification problem

MLModel contains class ModelUse. Initializing a class instance it is needed to initialize model preset, loss function and optimizer.
The class contains functions for training and evaluating the given model by passing required training/testing data

DataLoader contains DataLoader class which is used to read csv-file, preprocess data, dividing it into different groups of columns based on their data type,
which is marked manually. Classes imbalance is detected automatically. In case of disbalance SMOTE is used. The function to count the number of missing values for each column is defined

Visualizer contains two functions for visualizing. get_graphs() function realizes the choice of the graphs to be used.

main contains the example of using the above-mentioned modules, using the csv-file for an instance

How to use the modules:
1)Create files .py and copy the code from each module
2)Import classes from modules into your project
Defining the data type of the columns and passing keywords to transform binary data into binary form(0/1) (for DataLoader preprocessing), splitting data are on the user.
