# Bioinformatics_Project
1. Framingham dataset was given to us to prepare a classification model using Logistic Regression, SVM, KNN, Decision Tree.
2. Imported NumPy, Pandas, Matplot, Seaborn libraries.
3. Performed Exploratory Data Analysis to find out that education column is negatively correlating with the output.
4. Removed the education column and imputed good distributed columns with mean function.
5. Normalized the data using Standard Scaler and calculated eigenvectors and eigenvalues.
6. Calculated PC Values and plotted a scree plot with a threshod value of 95% cummulative error.
7. Selected 9 features which passed the threshold.
8. Created a model pipeline and dictionary of models.
9. Apllied the training data to models and trained them.
10. Calculated evaluation metrics like accuracy, precision, f1-score, recall using classification report.
11. Printed confusion matix for all the models.
12. Increased accuracy of Decision tree model by using 10 fold cross validation.
