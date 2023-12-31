# Equipments-Failures <img src="https://github.com/ValentinPatrakeev/Equipments-Failures/blob/main/broken%20machine.jpg" width="7%">

**It is necessary to predict equipment failure.**
> &ensp; **Initial data:**
<br/>&ensp; Various equipment operation data and recorded failures<br/>
> &ensp; **Goal:**
<br/>&ensp;  Conduct exploratory data analysis, find relationships (it is possible to explain the dependence - without training), train model

**Uploaded to the repository:**
* [Equipments-Failures](https://github.com/ValentinPatrakeev/Equipments-Failures/blob/main/Equipments-Failures.ipynb)
* Basic model (without training): **ROC_AUC - 0.884**
* Several modals were trained, the best one was selected, hyperparameters were selected: **ROC_AUC - 0.972 XGBClassifier**

### Main libraries used

![PANDAS](https://img.shields.io/badge/PANDAS-1.3.5-090909??style=flat-square&logo=PANDAS)
![NUMPY](https://img.shields.io/badge/NUMPY-1.21.5-090909??style=flat-square&logo=NUMPY)
![catboost](https://img.shields.io/badge/CATBOOST-1.2.1-090909??style=flat-square&logo=catboost)
![xgboost](https://img.shields.io/badge/XGBOOST-2.0.1-090909??style=flat-square&logo=catboost)
![lightgbm](https://img.shields.io/badge/LIGHTRGBM-2.0.1-090909??style=flat-square&logo=pydantic)
![optuna](https://img.shields.io/badge/OPTUNA-3.4.0-090909??style=flat-square&logo=psycopg2)

