# EXNO:4-DS
# AIM:
To read the given data and perform Feature Scaling and Feature Selection process and save the
data to a file.

# ALGORITHM:
STEP 1:Read the given Data.
STEP 2:Clean the Data Set using Data Cleaning Process.
STEP 3:Apply Feature Scaling for the feature in the data set.
STEP 4:Apply Feature Selection for the feature in the data set.
STEP 5:Save the data to the file.

# FEATURE SCALING:
1. Standard Scaler: It is also called Z-score normalization. It calculates the z-score of each value and replaces the value with the calculated Z-score. The features are then rescaled with x̄ =0 and σ=1
2. MinMaxScaler: It is also referred to as Normalization. The features are scaled between 0 and 1. Here, the mean value remains same as in Standardization, that is,0.
3. Maximum absolute scaling: Maximum absolute scaling scales the data to its maximum value; that is,it divides every observation by the maximum value of the variable.The result of the preceding transformation is a distribution in which the values vary approximately within the range of -1 to 1.
4. RobustScaler: RobustScaler transforms the feature vector by subtracting the median and then dividing by the interquartile range (75% value — 25% value).

# FEATURE SELECTION:
Feature selection is to find the best set of features that allows one to build useful models. Selecting the best features helps the model to perform well.
The feature selection techniques used are:
1.Filter Method
2.Wrapper Method
3.Embedded Method

# CODING AND OUTPUT:
![Screenshot 2024-11-19 114209](https://github.com/user-attachments/assets/dbe54a91-4e6a-4a82-baf3-c7dc2d8535af)
![Screenshot 2024-11-19 114228](https://github.com/user-attachments/assets/2e592eee-2851-49ce-a59b-a00420914ed9)
![Screenshot 2024-11-19 114244](https://github.com/user-attachments/assets/8b78254e-a2fa-4ca9-988a-f5a64be55a5b)
![Screenshot 2024-11-19 114303](https://github.com/user-attachments/assets/77f23b44-9af6-476f-9f9e-024c150335fa)
![Screenshot 2024-11-19 114324](https://github.com/user-attachments/assets/1929d82e-475a-4724-a980-9cc4082e860d)
![Screenshot 2024-11-19 114343](https://github.com/user-attachments/assets/7da8ce8a-e3f9-4852-b26d-eafda0cd82ec)
![Screenshot 2024-11-19 114402](https://github.com/user-attachments/assets/91c53815-904d-4538-b92a-9505a2b475ef)
![Screenshot 2024-11-19 114416](https://github.com/user-attachments/assets/9a169eb4-afb1-4405-b0e9-053869e8a531)
![Screenshot 2024-11-19 114451](https://github.com/user-attachments/assets/8ece1709-3764-4bc5-8854-05df2099e06e)

# RESULT:
       Thus, Feature selection and Feature scaling has been used on the given dataset.
