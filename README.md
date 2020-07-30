# TitanicKaggle
Kaggle Submissions

I had 2 different methods for my submissions: GLM model and Random Forest.

For both methods, I used Exploratory to filter out NA values and to create new variables like Title, FancyTitle, Marriage, and Agebracket using various filtering techniques. I filled out all the NA values with their mean value except for the variable Embarked for which I used the mode value "S".

After filtering and cleaning the data, I used a GLM model on Exploratory using the variables Embarked + Pclass + Agebracket + SibSp + Parch + Fare + Sex + Title and used the same model on the test data to predict the Survived test variable. The variables and model used above resulted in my highest score on Kaggle of 77.033%.

Using Random Forest on R, as seen in the file RandomForestCode, I imported the cleaned data sets from Exploratory and combined them appropriately to ensure all factor levels were the same and ran the Random Froest prediction which resulted in the slightly lower score of 76.076%.
