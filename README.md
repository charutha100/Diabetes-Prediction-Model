 Diabetes Prediction:

Tools Used:  
•	Python libraries:
•	Pandas: for data loading, cleaning and manipulation.
•	Scikit-learn: for prioritization, training and modelling (Naive Bayes, SVM, Random Forest).
•	Seaborn: for visualizing confusion matrices.
•	Matplotlib (optional): for additional plotting or visualization needs.


Working Procedure: 
•	Load and inspect data: 
•	Use “pandas.read_csv” to load data and inspect its structure, column type and data records.
•	Previous data:
- Removed “smoking_history” row to simplify data.
 Used to encode gender field as a number (Example = 0, Male = 1, Other = 2).
- Split dataset into features (“x”) and targets (“y”).
•	 Training-Test Split:
•	Use “train_test_split” to split data into training and testing; 80% for training and 20% for testing.
•	Training and testing models:
•	Used models:
- Naive Bayes (GaussianNB): a simple probabilistic classifier.
- Support Vector Machine (SVM): Robust classifier for binary data.
- Random Forest: Ensemble method for improved accuracy.  
•	Evaluated models using metrics like accuracy, confusion matrix, and 
distribution maps.
•	Visualization: 
•	Plot heatmaps of confusion matrices using seaborn to gain insight into 
performance patterns.

Learning Outcomes: 
•	Learn how to pre-process data, including entering categorical variables and dealing with redundant rows. 
•	Gain experience with train-test separation and selecting a size test. 
•	Explore and compare different learning models. 
•	 Learn how to use uncertainty matrices, accuracy, and other metrics to evaluate model performance. 
•	Advanced intelligence to visualize performance metrics for better translation.
