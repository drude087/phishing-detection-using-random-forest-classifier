Training:

This Python script utilizes scikit-learn to train a RandomForestClassifier on pre-saved datasets. 

It performs cross-validation, evaluates the model on a test set, prints the accuracy, and saves the model structure in 'classifier.json'. 

The 'dump' module aids in converting the classifier to a JSON format for analysis or visualization.

run-algorithm:

The script analyzes the performance of neural networks, random forests, and support vector machines on a specified dataset ("Dataset.csv" and "Target_Labels.csv"). 

It evaluates metrics such as accuracy, confusion matrices, and sensitivity/specificity, using a 30% test size, and reports the runtime for the entire process. 

The implemented models include a neural network, a random forest, and a support vector machine with specific configurations.

preprocess:

This Python script processes an ARFF dataset, selecting specific features, splitting it into training and testing sets, and saving the resulting data in NumPy files. 

Additionally, it creates a JSON file (`testdata.json`) containing the test data for potential external use, particularly in web applications or visualizations. 

The processed dataset, training, and testing sets are saved for further use in machine learning tasks.
