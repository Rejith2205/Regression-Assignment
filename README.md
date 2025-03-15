# Regression-Assignment
Regression Assignment Objective:  The objective of this assignment is to evaluate your understanding of regression techniques in supervised learning by applying them to a real-world dataset  

***Dataset:***
Use the California Housing dataset available in the sklearn library. This dataset contains information about various features of houses in California and their respective median prices.   

Key Components to be Fulfilled:  

***1.	Loading and Preprocessing***

○	Load the California Housing dataset using the fetch_california_housing function from sklearn.  
○	Convert the dataset into a pandas DataFrame for easier handling.  
○	Handle missing values (if any) and perform necessary feature scaling (e.g., standardization).  
○	Explain the preprocessing steps you performed and justify why they are necessary for this dataset.  

***2.	Regression Algorithm Implementation:***  

 Implement the following regression algorithms:  

○	Linear Regression  
○	Decision Tree Regressor  
○	Random Forest Regression  
○	Gradient Boosting Regression  
○	Support Vector Regression (SVR)  
 For each algorithm:  
○	Provide a brief explanation of how it works.  
○	Explain why it might be suitable for this dataset  


***3.	Model Evaluation and Comparison :***
○	Evaluate the performance of each algorithm using the following metrics:  
■	Mean Squared Error (MSE)  
■	Mean Absolute Error (MAE)  
■	R-squared Score (R²)  
○	Compare the results of all models and identify:  
■	The best-performing algorithm with justification 
■	The worst-performing algorithm with reasoning  

# "California Housing" Supervised Learning -Regression Evaluation

***Import Libraries***

![image](https://github.com/user-attachments/assets/16871e51-dd13-4cdc-993a-8bc0db9ae7e8)  
# ***1.	Loading and Preprocessing*** 

***Loading and Preprocessing--
Load the California Housing dataset using the fetch_california_housing function from sklearn***
![image](https://github.com/user-attachments/assets/0de773ba-cade-468b-82fa-b0bb33a29387)
***Convert the dataset into a pandas DataFrame for easier handling***  
![image](https://github.com/user-attachments/assets/2e2be332-dba1-4e61-9eed-81b6a2c866d9)
![image](https://github.com/user-attachments/assets/1ce19c10-62c1-4e04-bd5c-06f23d6012d1)
![image](https://github.com/user-attachments/assets/38343c1a-583a-4192-b8ae-6dfe1ba8a427)
![image](https://github.com/user-attachments/assets/655e6e42-b592-45f6-9212-2238315e1c91)
![image](https://github.com/user-attachments/assets/c3dcf6fa-afc9-495f-8529-2e38af15dcff)
![image](https://github.com/user-attachments/assets/1f75ddb6-9e35-477c-bd49-69ef9da113f2)
![image](https://github.com/user-attachments/assets/ff1b6052-2a57-446a-b832-5474bbc7720f)
![image](https://github.com/user-attachments/assets/b5eed6ab-fd7b-4621-a474-54df3b67544e)
![image](https://github.com/user-attachments/assets/283afcbc-ffae-41f5-a11f-6beb0dc46503)
![image](https://github.com/user-attachments/assets/f8a855ed-441c-41b7-b6f8-31c9b5dc8c08)
![image](https://github.com/user-attachments/assets/78616ff5-670d-4ec7-8351-1e1889d062c5)
![image](https://github.com/user-attachments/assets/84f949dd-af3e-4e7b-929f-f1298865c742)
![image](https://github.com/user-attachments/assets/b2eff3c8-bbb4-4a01-a72a-f9f207470de1)
![image](https://github.com/user-attachments/assets/e71858bb-c142-487b-87dc-766707ef032f)
![image](https://github.com/user-attachments/assets/f6a3fb86-7a22-4aef-a47f-798e8fe1bbd5)

***based on the skewness identify which is right skewed and which is left skewed if there is any symmetrical***   

***Skewness >               1.0 →              Highly skewed (right-tailed, large outliers).***  
 ***Skewness between      -1 and 1 →            Roughly normal (acceptable for models).***  
 ***Skewness <             -1.0 →               Highly left-skewed (rare in real estate data).***
    
    
    
    
    
    MedInc (Median Income)            	 1.6465          	  Moderately right-skewed  

    HouseAge (Median House Age)     	 0.0603	              Nearly symmetrical  

    AveRooms (Avg. Rooms per Household)	 20.6963	          Highly right-skewed (outliers present)


    AveBedrms (Avg. Bedrooms per Household)	  31.3147         Extremely right-skewed (outliers present)
    Population                      	4.9355                Highly right-skewed
    
    AveOccup (Avg. Occupants per Household)	97.6324	          Extremely right-skewed (severe outliers)
    
    Latitude	                        0.4659	              Slightly right-skewed
    
    Longitude	                        -0.2977	              Slightly left-skewed
    
    Target (House Price in $100,000s)	0.9776	              Moderately right-skewed

    ***IQR Outlier Removal***

    ![image](https://github.com/user-attachments/assets/d64d8ba6-339f-4692-b5da-f672c28a3f00)
![image](https://github.com/user-attachments/assets/5c32a172-312f-4a5e-a2d4-752a19b5cff4)
![image](https://github.com/user-attachments/assets/02db5d64-d07b-4a55-8037-e35c365239da)
![image](https://github.com/user-attachments/assets/9fb37c23-4e87-4958-bde7-5b291263f986)
![image](https://github.com/user-attachments/assets/5ece598f-595a-4846-b61a-73abc3bbc763)
![image](https://github.com/user-attachments/assets/7e4fa470-5f83-4e9b-8b93-ae626be49ff8)



