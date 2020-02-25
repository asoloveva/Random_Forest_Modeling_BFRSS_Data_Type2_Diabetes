# Random_Forest_Modeling_BFRSS_Data_Type2_Diabetes
Predicting risk factors of Type 2 Diabetes
Analyses implements two models: Desesion Tree and Random Forest. It is based on two reserch studies 'Building Risk Prediction Models for Type 2 Diabetes Using Machine Learning Techniques' by Xie Z, Nikolayeva O, Luo J, Li D. and 'Developing risk prediction models for type 2 diabetes: a systematic review of methodology and reporting.' by Collins GS, Mallett S, Omar O, Yu LM.
As files of BRFSS Survey data presented with formats which are different from csv format, I've used Winston Larson work on github where he has done an extensive work on BRFSS data extracting and cleaning.

Results:
Single Decesion Tree
1. ROC AUC: 0.59
2. RMSE: 0.972
3. Cross-Validation Score: 0.977


Random Forest
1. ROC AUC:  0.78
2. Out-of-Bag Error score: 0.84
3. Cross-Validation Score: 0.80
