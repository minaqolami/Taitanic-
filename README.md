# Titanic
This project is an analysis of the Titanic dataset using Exploratory Data Analysis (EDA) and various machine learning algorithms. This project aims to predict whether a passenger survived or not based on several features.


## Dataset
The dataset contains 891 observations and 12 variables including a binary variable, Survived, which indicates whether a passenger survived or not. 
Dependencies
The project requires the following Python libraries:
- pandas
- NumPy
- seaborn
- matplotlib
- sci-kit-learn


## Exploratory Data Analysis (EDA)
EDA is performed on the training dataset to understand the relationships between variables and to identify any patterns or trends. The following visualizations are used:
- Histograms to visualize the distribution of numerical variables.
- Bar plots to visualize the count of categorical variables.
- Heatmap to visualize the correlation between variables.
- Boxplots to visualize the relationship between numerical and categorical variables.
## Machine Learning Models
- The following machine learning models are used to predict the survival of passengers:
- K-Nearest Neighbors (KNN)
- Logistic Regression
- Random Forest
- Support Vector Machine (SVM)
- Linear Discriminant Analysis (LDA)
The models are trained on the training dataset and evaluated on the test dataset using an accuracy score. 
## Conclusion
EDA shows that variables such as Sex, Pclass, and Age have a significant impact on the survival of passengers. The machine learning models perform well on the dataset with KNN having the highest accuracy score of 0.82. The model can be used to predict the survival of passengers based on their features.
