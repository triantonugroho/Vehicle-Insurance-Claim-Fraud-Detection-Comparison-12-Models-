## Vehicle Insurance Claim Fraud Detection (Comparison 12 Models) 

* ### This project looks for the best model performance from 12 classification models to detect fraud in automobile insurance claims. The best model is the Ada Boost Classifier with 95.90% accuracy.

![1](https://user-images.githubusercontent.com/91950433/218259682-75e70132-565c-4b59-844b-87a0ff0ed987.png)

### Data Understanding

![2](https://user-images.githubusercontent.com/91950433/218259695-6a7253e0-891b-475c-a676-6b04cb069d68.png)

* #### Vehicle Insurance Fraud Detection
Vehicle insurance fraud involves conspiring to make false or exaggerated claims involving property damage or personal injuries following an accident. Some common examples include staged accidents where fraudsters deliberately “arrange” for accidents to occur; the use of phantom passengers where people who were not even at the scene of the accident claim to have suffered grievous injury, and make false personal injury claims where personal injuries are grossly exaggerated.

* #### About this dataset
This dataset contains vehicle dataset - attribute, model, accident details, etc along with policy details - policy type, tenure etc. The target is to detect if a claim application is fraudulent or not - FraudFound_P

* #### Source
https://www.kaggle.com/datasets/shivamb/vehicle-claim-fraud-detection

* #### Dimension
The data contains 15.421 rows and 33 columns

### Exploratory Data Analysis (EDA)

* #### Import Library

* #### Upload Dataset

* #### Read Dataset

* #### Display 5 Samples

* #### Dataset Information

* #### Checking Missing Values

* #### Checking Data Duplicates

* #### Checking Shape or Dimension

* #### Checking Label Proportion

* #### Descriptive Statistic

* #### Histogram

* #### Pair Plot

* #### Correlation Matrix

* #### Checking for Multicolinearity

* #### Checking Number of Unique Values

* #### Remove Unnecessary Columns

### Data Preprocessing

* #### Separating the feature and target columns

* #### Encoding Categorical Columns

* #### Extracting Categorical Columns

* #### Printing Unique Values of Each Columns

* #### Get Dummies from Categorical Columns

* #### Extracting the Numerical Columns

* #### Combining Numerical and Categorical Columns

* #### Normalization / StandarScaler()

* #### Outliers Detection

* #### Balancing the Dataset using oversampling (SMOTE)

* #### Reduce Overfitting using Principal Component Analysis (PCA)

* #### Split Dataset

### Modeling

#### 1. Support Vector Classifier
#### 2. KNN
#### 3. Decision Tree Classifier
#### 4. Random Forest Classifier
#### 5. Ada Boost Classifier
#### 6. Gradient Boosting Classifier
#### 7. Stochastic Gradient Boosting (SGB)
#### 8. XgBoost
#### 9. Cat Boost Classifier
#### 10. Extra Trees Classifier
#### 11. LGBM Classifier
#### 12. Voting Classifier

### Models Performance Comparison

![comparison plot](https://user-images.githubusercontent.com/91950433/218281537-0b5e8a17-8085-440c-aa76-e4ef5e5d05b9.png)

### Conclusions
* #### Best Model : Ada Boost Classifier
* #### Accuracy : 0.958958 (95,90 %)
