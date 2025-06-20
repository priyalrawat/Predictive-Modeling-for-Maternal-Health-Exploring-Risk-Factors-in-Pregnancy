# Predictive-Modeling-for-Maternal-Health-Exploring-Risk-Factors-in-Pregnancy

**Introduction**

Maternal Health Risk Prediction is more of a life safer task than a technical change, it can have a life-altering impact on the health of both mother and an infant. It is one of the major and important issue. If the maternal health risk can be assessed and identified before a mother's delivery, opportunities for timely interventions can result in saving lives and decrease complications. With the help of machine learning models, including Random Forest and Support Vector Machine (SVM), Gradient Boosting, we can determine maternal health risks based on a variety of data including age, blood pressure and glucose levels (Al Mashrafi, Tafakori, & Abdollahian, 2024).  This study explores how we can utilize these algorithms in predicting risk for maternal health and formulate a promising approach towards expectant mothers and their babies (Pi, Wang, Chu, Zhang, & Zhang, 2025).

**Methodology**

This study analyzed a maternal health dataset downloaded from Kaggle with variables such as age, blood pressure (BP), glucose level, heart rate as predictors to examine the RiskLevel of pregnancies. After confirming that there were no missing values,  all numerical values were standardized using a StandardScaler. Exploratory data analysis (EDA) was performed, which includes histograms, boxplots, and correlation heatmaps to understand the distribution and correlation of features in the dataset. Three machine learning models were developed which are support vector machine (SVM), random forest, and gradient boosting. Hyperparameter tuning was done through GridSearchCV to create optimized configurations for the models. Feature importance was done from the random forest model to recognize the most significant predictors. Finally, model performance was evaluated using Accuracy, Precision, Recall, F1-Score, and AUC-ROC.

**Conclusion**

The goal of this study was to predict maternal health risk using machine learning models such as SVM, Random Forest, and Gradient Boosting. Exploratory Data Analysis was done to identify clear relationships between SystolicBP and DiastolicBP as they increased together. BodyTemp and Age had weak relationships with the other variables analysed. From histograms, it was evident that BS and SystolicBP were right skewed which indicated the presence of possible outliers. After hyper-parameter tuning, the random forest model best performed in prediction, with blood sugar increasing in importance as the best predictor. The key health indicators outlined in this study are significant predictors of high risk maternal health levels. This research is important because it can allow healthcare providers to make better decisions which can assist with maternal and infant outcomes. Future work we expect to integrate or include additional factors such as using lifestyle data, real time monitoring systems, and deep learning can greatly increase the accuracy of predictions and clinical value, as well as provides a promising pathway to provide better prediction of mothers at risk in a more dynamic and accurate sense.

**References**

Al Mashrafi, S. S., Tafakori, L., & Abdollahian, M. (2024). Predicting maternal risk level using machine learning models. BMC Pregnancy and Childbirth. https://bmcpregnancychildbirth.biomedcentral.com/articles/10.1186/s12884-024-07030-9
Pi, X., Wang, J., Chu, L., Zhang, G., & Zhang, W. (2025). Prediction of high-risk pregnancy based on machine learning algorithms. Scientific Reports, 15(1), 1-11. https://www.nature.com/articles/s41598-025-00450-3

