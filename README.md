# Credit_Risk_Analysis
#Overview of Analysis:
Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Varying machine learning algorithms were utilized for training and evaluation of models.

#Delverables

Create training and test groups from a given data set.

Implement the logistic regression, decision tree, random forest, and support vector machine algorithms.

Interpret the results of the logistic regression, decision tree, random forest, and support vector machine algorithms.

Compare the advantages and disadvantages of each supervised learning algorithm.

Determine which supervised learning algorithm is best used for a given data set or scenario.

Use ensemble and resampling techniques to improve model performance.


#Tools: Python, Jupiter notebook, imblearn, scikit-learn, smote algorithm, clustercentroids, randomforestclassifier, easyensembleclassifier

#Results 
#Naive Random oversampling
<img width="570" alt="Screen Shot 2022-10-26 at 9 00 16 AM" src="https://user-images.githubusercontent.com/80330988/198032440-c251aa15-74cf-4d10-baa5-9b85954bf4aa.png">
Balanced Accuracy:  0.647978937275141

#Smote Oversmapling 
<img width="578" alt="Screen Shot 2022-10-26 at 9 02 31 AM" src="https://user-images.githubusercontent.com/80330988/198032785-8372d445-4cc0-455f-8378-92e3cd9ad1e3.png">
Balanced Accuracy:  0.6361714428449988


#Undersampling
<img width="567" alt="Screen Shot 2022-10-26 at 9 04 10 AM" src="https://user-images.githubusercontent.com/80330988/198033088-f21bc2a3-e1ed-4ecf-8d86-0fa93aa46296.png">
Balanced Accuracy: 0.5293318990697431


#Combination over-under sampling
<img width="567" alt="Screen Shot 2022-10-26 at 9 05 12 AM" src="https://user-images.githubusercontent.com/80330988/198033305-9aabfabc-1683-48ff-81d8-c21414656117.png">
Balanced Accuracy:  0.5293318990697431


#Balanced Random forest 
<img width="569" alt="Screen Shot 2022-10-26 at 9 06 59 AM" src="https://user-images.githubusercontent.com/80330988/198033701-4f4b6e94-9c4a-4726-91f2-820b922647d6.png">
Balanced Accuracy: 0.7877672625306695


#Easy Ensemble Adaboost Classifier
<img width="570" alt="Screen Shot 2022-10-26 at 9 07 54 AM" src="https://user-images.githubusercontent.com/80330988/198033902-6a0e3381-5e78-4184-a750-5a6dd19eb84b.png">
Balanced Accuracy: 0.9197970678173006


#Summary
In conclusion based on the results from the created test models, the easy ensemble adaboost classifier is the best performing model to utilize for credit risk analysis. The adaboost classifier recieved a balanced accuracy of 91.97. 
