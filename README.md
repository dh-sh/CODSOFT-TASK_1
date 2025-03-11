Issues Faced During Execution of the Titanic Survival Prediction Project  

Data Preprocessing Issues  
Missing values in key columns like Age, Cabin, and Embarked caused errors.  
Categorical variables like Sex and Embarked needed encoding to be used in machine learning models.  
Non-numeric features like Name, Ticket, and Cabin had to be dropped.  

Data Splitting and Normalization Issues  
The initial dataset split was imbalanced, affecting model training.  
Standardization using StandardScaler led to errors due to missing values.  

Model Training and Performance Issues  
Class imbalance resulted in biased predictions.  
Logistic Regression had lower recall for survivors, meaning some actual survivors were misclassified.  
Random Forest performed better but had a slight risk of overfitting.  

Debugging and Code Errors  
Attribute errors occurred when accessing DataFrame columns.  
Issues arose with NumPy arrays not supporting DataFrame operations.  
Runtime warnings from Scikit-Learn appeared due to NaN values in feature scaling.  

Final Thoughts and Future Improvements  
Hyperparameter tuning could improve model performance.  
Advanced models like XGBoost or LightGBM could be tested.  
Feature engineering could create new, meaningful variables for better predictions.
