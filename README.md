# scoring_model

Objectif : Mettre en place un modèle de scoring pour prédire si un emprunteur va rembourser son prêt.

Origine du projet : https://www.kaggle.com/competitions/home-credit-default-risk

Source des données utilisées : 
				application_train.csv
				application_test.csv

Dans ce projet les méthodes suivantes ont été utilisées : 
	
	Label encoding
	One hot encoding
	GridSearchCV
	RepeatedStratifiedKFold
	Feature engineering

Les modéles de machine learning suivants ont été testés : 

	Logistic Regression (avec class_weight = balanced)
	Logistic Regression (avec SMOTE)
	SVM
	Random Forest Classifier
	XGBoost
	LightGBM

Pour l'interprétabilité des modéles : 

	feature_importances_	
	SHAP

