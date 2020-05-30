# fifa 2018 Winner Predication by Mithilesh thakkar
This is a **python** implementation of the **fifa(football worldcup) 2018** each match's winner and final winner.

The purpose of this is to try and predict the top 3 teams for World Cup 2018 using classification models coupled with poisson distribution to predict the exact results of the semi-finals, third place playoff and final. 

## **Final Predictions based on this notebook:**

**Winner**: Germany

**2nd Place**: Spain

**3rd Place**: France

### And they are **same** as the **results of the FIFA 2018**.

## **Contents:**

### **1. Import Necessary Packages/Datasets** 
- **Numpy** (for implementation of basic **linear algebra operation**)
- **Pandas** (for **data analysis and manipulation**)
- **Matplotlib** (for **ploting the graph**)
- **Seaborn** (for **statistical data visualization**)
- **Sklearn** (for **implemanting different classifiers**)

### **2. Data Cleaning**
- This is done for making the **[dataset](https://www.kaggle.com/ahmedelnaggar/fifa-worldcup-2018-dataset) useable for our prediction**

### **3. Classification Models to predict match results (Win/Draw/Lose)**
- classifier used:
  - First I have used the basic **logistic regression** method to predict the winner.
  
## Results
- Currently I am getting the winner with the accuracy of **57% using the logistic regression**..

## Future Work
- And I will try to use the **XGBoosting,Random Forest, Decision Tree, K-Nearest Neighbour and SVM (Linear Kernel).** classifier to predict the winner which can increase the accuracy.

## Acknoweldgement
- I acknowelde ahmedelnaggar for providing the [dataset](https://www.kaggle.com/ahmedelnaggar/fifa-worldcup-2018-dataset) for the preication.
