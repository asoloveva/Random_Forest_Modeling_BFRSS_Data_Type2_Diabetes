# Random_Forest_Modeling_BFRSS_Data_Type2_Diabetes
Predicting risk factors of Type 2 Diabetes
Analyses implements two models: Desesion Tree and Random Forest. It is based on two reserch studies 'Building Risk Prediction Models for Type 2 Diabetes Using Machine Learning Techniques' by Xie Z, Nikolayeva O, Luo J, Li D. and 'Developing risk prediction models for type 2 diabetes: a systematic review of methodology and reporting.' by Collins GS, Mallett S, Omar O, Yu LM.
As files of BRFSS Survey data presented with formats which are different from csv format, I've used Winston Larson work on github where he has done an extensive work on BRFSS data extracting and cleaning.


Conclusion
1. Defined feature columns and independent variable which is diabetes3
2. Splitted the data on training and testing sets assigning 70% and 30% respectevely
3. Used various statistical libraries along with Scikit-Learn library which provides Random Forest classifier function
4. Fitted the model on the Training Data
5. Used fitted model to make predictions on Testing Data

Results: 

Single Decesion Tree
ROC AUC: 0.59
Cross-Validation Score: 0.76

Random Forest
ROC AUC: 0.78
Out-of-Bag Error score: 0.84
Cross-Validation Score: 0.84
