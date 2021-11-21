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

**2. Numerical Feature-set Distribution**

![image](https://user-images.githubusercontent.com/54996245/142728603-1e3c1c51-924b-48b1-9f2d-69667e453d41.png)
![image](https://user-images.githubusercontent.com/54996245/142728605-8c11add5-a64b-4d2b-bdc3-bbaa79f848d0.png)


**3. Relationship between the Feature-set**

![image](https://user-images.githubusercontent.com/54996245/142728609-bb82d861-e295-4862-ae5b-0db33eb47c50.png)

**4. Data Retention after preforming preprocessing step**

![image](https://user-images.githubusercontent.com/54996245/142728619-19bf98bb-9e15-40c6-a8cb-b1a6093324e0.png)

**5. Correlation Plot**

![image](https://user-images.githubusercontent.com/54996245/142728629-2b4c04f5-cf2e-4beb-9649-645297ab809d.png)

**6. Multiple Linear Regression Prediction & Residual Normality Check**

![image](https://user-images.githubusercontent.com/54996245/142728650-8dbc0ac6-73d2-4c58-913e-fc6d0b930fcc.png)

**7. Polynomial Degrees Comparison**

![image](https://user-images.githubusercontent.com/54996245/142728667-d7dd89e5-378f-43f8-8c2e-f2eacad68934.png)

**8. Predictions**

![image](https://user-images.githubusercontent.com/54996245/142728697-ccf4d1f4-997b-42ba-af37-c3a6fdcc8d88.png)


**9. ML Algorithm's Scores Comparison (R2& RMSE) for the Ad Budge Dataset**

![image](https://user-images.githubusercontent.com/54996245/142728707-219e1a93-b5c2-4ff0-973f-488df92488dd.png)
![image](https://user-images.githubusercontent.com/54996245/142728711-60a1ea62-6427-472d-bc40-58e48b2847c4.png)


### Here are some of the key outcomes of the project:
- The Dataset was quiet small totally just 100 samples & after preprocessing none of the datasamples were dropped. 
- Visualising the distribution of data & their relationships, helped us to get some insights on the feature-set.
- The features had some multicollinearity, but since we had only 2 features, we did not perform any feature selection/extraction.
- Testing multiple algorithms with hyperparamter-tuning gave us some understanding for various models performance on this specific dataset.
- While, Polynomial Regression (Order-2) gave the best overall scores for the current dataset, yet it wise to also consider simpler models like MLR & ENR as they are more generalisable.
