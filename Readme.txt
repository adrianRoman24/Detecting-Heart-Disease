	Detecting Heart Disease
	
	The aim of this project is to find corelations between different medical
features of a patient and to try to predict whether or not they have heart
disease. The target accuracy of the model is 95% and the aproach to obtain
it implies trying different machine learning models such as:LogisticRegression,
KNeighborsClassifier and RandomForestClassifier and by tunning the hyperparameters
of these models.

	The tools that are used in this notebook are Python-based machine learning
data science libraries: Scikit-Learn, Pandas, Numpy and Matplotlib.
	
	The features taken into consideration when evaluating the medical condition
of a patient are:
	1. age - age in years\n;
    2. sex - 1 = male, 0 = female;
    3. cp - chest pain type:
        * 0: Typical angina,
        * 1: Atypical angina,
        * 2: Non-anginal pain,
        * 3: Asymptomatic;
    4. trestbps - resting blood pressure (in mm Hg on admission to the hospical);
    5. chol - serum cholesterol in mg/dl\n;
    6. fbs - fasting blood sugar > 120 mg/dl (1 = true, 0 = false);
    7. restecg - resting electrocariographic results:
        * 0: Nothing to note,
        * 1: ST-T Wave abnormality,
        * 2: Possible or definite left ventricular hypertrophy;
    8. thalach - maximum heart rate achieved;
    9. exang - exercise induced angina (1 = yes, 0 = no);
    10. oldpeak - ST depression induced by exercise relative to rest;
    11. slope: the slope of the peak exercise ST segment:
        * 1: upsloping,
        * 2: flat,
        * 3: downsloping;
    12. ca - number of major vessels (0-3) colored by flourosopy;
    13. thal - 3 = normal, 6 = fixed defect, 7 = reversable defect;
    14. num (target) - patient has heart disease or not (1 = yes; 0 = no).
	
	The processed data can be found at: https://archive.ics.uci.edu/ml/datasets/heart+disease
	
	