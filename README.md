# Coronary Heart Disease Classification and Linear Regression Systems
1) Problem Statement:
  - Coronary Heart Disease (CHD) involves the reduction of blood flow to the heart muscle due to build -up of plaque in  the arteries of the heart. 
  - Risk factors include hypertension, smoking , diabetes, obesity, and high cholesterol.
  - In 2017, 110 million people were diagnosed with Coronary Heart Disease (CHD) resulting in 8.9 million deaths, making it the most common death globally.
  - Early prognosis of CHD in high risk patients can aid in making decisions on lifestyle changes. If caught in time, lifestyle changes will reduce complications and thus save lives.
  - There are two parts in this research: 
  - Linear Regression Model is used to determine if other risk factors have a significant impact on BMI 
  - Logistic Regression Model is used to classify whether or not the patients will have CHD within ten years given having other risk factors.
2) Multiple Linear Regression:
   - H0 :  βage =  βmale = βeducation = βcigsPerDay= βBMI= …. = βglucose = 0
   - Ha :  βage ≠ βmale ≠ βeducation ≠ βcigsPerDay≠βBMI= …. ≠ βglucose

   - At least one of the predictors  such as age, male, education, glucose, ... useful in predicting the BMI
   - Do all the predictors help to explain the correlation with BMI , or is only a subset of the predictors useful?
   - What methods do we use: Forward, Backward, or Mix Selection?
   - How well does the model fit the data?
   - Adjusted R-Squared: Increases or decrease if added features improve model
3)Interpreting the Results: 
   - This fitted model shows that, holding all other features constant, the odds of getting diagnosed with CHD:
   - With one unit increase in diaBP associates with 0.12 increase in BMI
   - Increasing diabetes one unit will lead to an increase of 1.99 in BMI
   - There is a 1.28% decrease in BMI for current smoker person. (Smokers are usually thin!)
   - Education has an inverse effect on BMI 
   - The odds of getting high BMI for males over that of female is 74%
4) Conclusion:
  - The true positive rate is more important than the false positive rate because it determines the percentage of patients with CHD who are correctly identified and warned.
  - When TPR = 0.9, we correctly identify and warn 90 out of 100 patients with CHD. 
  - However, at the same time, FPR = 0.6 meaning that more than half of the time, we incorrectly warn a patient about CHD who is actually healthy!!!
  -  We need another model with enhanced accuracy that predicts better results. 
This may be achieved with data sets identifying the critical, specific factors present in patients with CHD.
  - We can also increase the size of datasets if it is available.
  - Due to the diversity of the given data, more time is needed to enhance the model fidelity.
  - The bottom line is these features included in the dataset are not the best predictors for CHD
