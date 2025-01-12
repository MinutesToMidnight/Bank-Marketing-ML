Currently modules are designed for multiclassification problem
MLModel contains class ModelUse. Initializing a class instance it is needed to initialize model preset, loss function and optimizer.
The class contains functions for training and evaluating the given model by passing required training/testing data

DataLoader contains DataLoader class which is used to read csv-file, preprocess data, dividing it into different groups of columns based on their data type,
which is marked manually. Classes imbalance is detected automatically. In case of disbalance SMOTE is used. The function to count the number of missing values for each column is defined

Visualizer contains two functions for visualizing. get_graphs() function realizes the choice of the graphs to be used.

main contains the example of using the above-mentioned modules, using the csv-file for an instance
