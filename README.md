# AI/ML Project: Student Marks Prediction 📚
<p align="center"><img src="https://user-images.githubusercontent.com/54996245/142776524-363e18eb-cee9-48ce-9880-de372488161e.jpg" style="width: 1000px;"/></p>

### Description:

The data consists of Marks of students including their study time & number of courses. The dataset is downloaded from UCI Machine Learning Repository.

**Properties of the Dataset:** \
Number of Instances: 100\
Number of Attributes: 3 including the target variable.

The project is simple yet challenging as it is has very limited features & samples. Can you build regression model to capture all the patterns in the dataset, also maitaining the generalisability of the model?

### Objective:
- Understand the Dataset & perform the necessary cleanup.
- Build Regression models & fine-tune the hyperparamters to predict the student marks.
- Also evaluate the models & compare thier respective scores like R2, RMSE, etc.

### <center> Stractegic Plan of Action:
  
**We aim to solve the current problem statement by creating plan of action, Here are some of the necessary steps:**
1. Data Exploration
2. Exploratory Data Analysis (EDA)
3. Data Pre-processing
4. Feature Selection/Extraction
5. Predictive Modelling
6. Project Outcomes & Conclusion

### Some Visuals of the Project:
**1. Target Variable Distribution**

<p align="left"><img src="https://user-images.githubusercontent.com/54996245/142776603-1f060bd7-7929-499a-99d6-415bedd211b4.png" /></p>

**2. Categorical Feature-set Distribution**
  
![image](https://user-images.githubusercontent.com/54996245/142776610-1466c50e-76be-4130-bd6f-f7ded8d6c036.png)
![image](https://user-images.githubusercontent.com/54996245/142776614-917c4679-b2ba-4bcd-88e5-c0924879450b.png)

**3. Numerical Feature-set Distribution**

![image](https://user-images.githubusercontent.com/54996245/142776650-9319526e-3a19-446d-a4be-4d1fdc090f19.png)
![image](https://user-images.githubusercontent.com/54996245/142776644-1ff37a2e-d4dd-4fd3-9e9b-62e43ba07084.png)


**4. Relationship between the Feature-set**

![image](https://user-images.githubusercontent.com/54996245/142776682-e8e4a052-209a-4caa-8ae2-096ada20a1a7.png)

**5. Data Retention after preforming preprocessing step**

![image](https://user-images.githubusercontent.com/54996245/142776685-dcfdb6d5-f956-4a8d-becd-3ccb67025644.png)

**6. Correlation Plot**

![image](https://user-images.githubusercontent.com/54996245/142776693-f2c3b455-8aaf-4b92-a2ce-e80e05523e03.png)

**7. Multiple Linear Regression Prediction & Residual Normality Check**

![image](https://user-images.githubusercontent.com/54996245/142776700-3bdd0ffd-c5fb-485f-bd2b-6c681cdeeebb.png)

**8. Polynomial Degrees Comparison**

![image](https://user-images.githubusercontent.com/54996245/142776711-01dc9a9a-9372-4394-b3a1-ecb243ced249.png)

**9. Predictions**

![image](https://user-images.githubusercontent.com/54996245/142776716-722f804a-6b40-4ebe-99a7-0b8cef3989ae.png)


**10. ML Algorithm's Scores Comparison (R2& RMSE) for the Ad Budge Dataset**

![image](https://user-images.githubusercontent.com/54996245/142776722-bdf15220-9c4b-4a11-a23e-e98f83f1cc81.png)
![image](https://user-images.githubusercontent.com/54996245/142776728-79c85193-41cf-4c3c-a60b-d94eeb728c05.png)


### Here are some of the key outcomes of the project:
- The Dataset was quiet small totally just 100 samples & after preprocessing none of the datasamples were dropped. 
- Visualising the distribution of data & their relationships, helped us to get some insights on the feature-set.
- The features had some multicollinearity, but since we had only 2 features, we did not perform any feature selection/extraction.
- Testing multiple algorithms with hyperparamter-tuning gave us some understanding for various models performance on this specific dataset.
- While, Polynomial Regression (Order-2) gave the best overall scores for the current dataset, yet it wise to also consider simpler models like MLR & ENR as they are more generalisable.
