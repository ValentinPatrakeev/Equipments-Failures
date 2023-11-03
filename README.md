# Equipments-Failures

### Задача - Необходимо по наблюдаемым признакам классифицировать отказ оборудования 
<img src="https://github.com/ValentinPatrakeev/Equipments-Failures/blob/main/broken%20machine.jpg" width="60%">

### Цель - Провести разведочный анализ данных, найти взаимосвязь данных (возможно объяснить зависимость - без обучения), обучить модель

### Результаты: 
* **Базовая модель (без обучения) : ROC_AUC - 0.884**
* **Обучены несколько медалей, выбрана лучшая, подобраны гиперпараметры : ROC_AUC - 0.972** **XGBClassifier**

### Основные используемые библиотеки 

![PANDAS](https://img.shields.io/badge/PANDAS-1.3.5-090909??style=flat-square&logo=PANDAS)
![NUMPY](https://img.shields.io/badge/NUMPY-1.21.5-090909??style=flat-square&logo=NUMPY)
![catboost](https://img.shields.io/badge/CATBOOST-1.2.1-090909??style=flat-square&logo=catboost)
![xgboost](https://img.shields.io/badge/XGBOOST-2.0.1-090909??style=flat-square&logo=catboost)
![lightgbm](https://img.shields.io/badge/LIGHTRGBM-2.0.1-090909??style=flat-square&logo=pydantic)
![optuna](https://img.shields.io/badge/OPTUNA-3.4.0-090909??style=flat-square&logo=psycopg2)

