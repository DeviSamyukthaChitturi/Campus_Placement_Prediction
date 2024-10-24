# Campus_Placement_Prediction
### IMPORTANCE: 
The Placement of students is one of the most important objective of an educational institution. Reputation and yearly admissions of an institution invariably depend on the placements it provides it students with. That is why all the institutions, arduously, strive to strengthen their placement department so as to improve their institution on a whole. Any assistance in this particular area will have a positive impact on an institution’s ability to place its students. This will always be helpful to both the students, as well as the institution.

### Overview
This project aims to predict student placements during campus recruitment processes using various machine learning models. The dataset includes key features such as academic performance, work experience, and employability test scores, with a target variable indicating placement status.

### Dataset
The dataset used is the Campus Placement Prediction dataset from Kaggle, containing 215 records and 14 features. It has been preprocessed to handle missing values and class imbalance, ensuring better model performance.

### Models Used
* Logistic Regression
* Support Vector Machine (SVM)
* Decision Tree
* Random Forest
* Voting Classifier

### Key Findings
* SVM showed the highest accuracy and F1 score, making it the best model for placement prediction.
* The Voting Classifier improved precision and F1 score by combining multiple models.

### How to Use
1. Clone the repository.
2. The dataset and project files are included for model training and evaluation.
3. The trained Voting Classifier model is saved in voting_classifier_model.pkl for future use.

### License
This project is for educational purposes only.
