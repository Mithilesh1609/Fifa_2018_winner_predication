# Fifa_2018_winner_predication
This is a **python** interpretation of the **fifa(football worldcup) 2018** each match's winner and final winner.

The purpose of this is to try and predict the top 3 teams for World Cup 2018 using classification models coupled with poisson distribution to predict the exact results of the semi-finals, third place playoff and final. 

## **Final Predictions based on this notebook:**

**Winner**: Germany

**2nd Place**: Spain

**3rd Place**: France


## **Contents:**

### **1. Import Necessary Packages/Datasets** 
- **numpy** (for implementation of basic **linear algebra operation**)
- **pandas** (for **data analysis and manipulation**)
- **matplotlib** (for **ploting the graph**)
- **seaborn** (for **statistical data visualization**)
- **sklearn** (for **implemanting different classifiers**)

### **2. Data Cleaning**
- this is done for making the **dataset useable for our prediction**

### **3. Classification Models to predict match results (Win/Draw/Lose)**
- classifier used:
  - first I have used the basic l**ogistic regression** method to predict the winner.
  - And I trying to use the **XGBoosting,Random Forest, Decision Tree, K-Nearest Neighbour and SVM (Linear Kernel).**

## Results
- Currently I am getting the winner with the accuracy of **57% using the logistic regression**.
  
