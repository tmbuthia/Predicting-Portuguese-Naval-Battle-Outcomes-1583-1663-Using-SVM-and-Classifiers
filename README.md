# Predicting-Portuguese-Naval-Battle-Outcomes-Using-SVM-and-Classifiers
This repository contains a project that uses different classification models to predict the outcomes of Portuguese naval battles between 1583 and 1663. The dataset includes information on naval battles involving Portuguese, Dutch, and English ships, as well as Spanish involvement.

Dataset
This project includes the following features:

Battle: Name of the battle place
Year: Year of the battle
Portuguese ships: Number of Portuguese ships
Dutch ships: Number of Dutch ships
English ships: Number of ships from the English side
The ratio of Portuguese to Dutch/British ships: Ratio of Portuguese ships to Dutch/British ships
Spanish Involvement: 1 = Yes, 0 = No
Portuguese outcome: -1 = Defeat, 0 = Draw, 1 = Victory
Models Used
The project evaluates the performance of several classifiers on the dataset:

Support Vector Machines (SVM)

Linear Kernel
Polynomial Kernel
RBF Kernel
Random Forest Classifier

Logistic Regression

Instructions
Load and Prepare Data

The dataset is loaded and prepared for modeling. The features are standardized, and the data is split into training and testing sets.

Train and Evaluate Models

SVM Models:

Linear Kernel: Standard linear SVM classifier.
Polynomial Kernel: SVM with polynomial kernel of degree 3.
RBF Kernel: SVM with RBF kernel.
Random Forest:

Random Forest classifier with default settings.
Logistic Regression:

Logistic Regression classifier with increased maximum iterations for convergence.
Performance Evaluation

The performance of each model is evaluated using accuracy, mean squared error, and classification reports.

Results
![image](https://github.com/user-attachments/assets/b17509e4-8919-4d5e-b52c-2157625a998e)


Linear SVM: Achieved 33.33% accuracy, with challenges in classifying classes, particularly class 1.
Polynomial SVM: Achieved 50% accuracy, with better performance compared to linear SVM but still struggles with certain classes.
RBF SVM: Achieved 50% accuracy, similar to Polynomial SVM in performance.
Logistic Regression: Similar performance to linear SVM with 33.33% accuracy and poor class classification.
Random Forest: Achieved the highest accuracy at 50%, performing slightly better in terms of F1-score and precision for some classes.
Conclusion
The models demonstrated varying performance levels. The Random Forest classifier showed the best overall accuracy and F1-scores for some classes. SVM models, especially with polynomial and RBF kernels, performed similarly and faced difficulties in distinguishing certain classes.
