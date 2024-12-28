# Analysis of Seattle Building Energy Consumption 🏢💡  
*(French version below)*  

This project focuses on analyzing and modeling energy consumption data from Seattle buildings for 2015 and 2016.  

## Key Topics 📝  

1. **Context and Dataset Overview**  
   - Energy consumption data for Seattle buildings.  
   - Details on data size, null values, and non-null values.  

2. **Data Cleaning and Preprocessing 🧹**  
   - Filtering columns with a high percentage of null values.  
   - Handling duplicates and outliers.  

3. **Exploratory Data Analysis (EDA) 🔍**  
   - Univariate and bivariate data analysis.  
   - Identifying correlations between variables.  

4. **Modeling 🧠**  
   - Creation of predictive models for:  
     - Total energy consumption.  
     - CO2 emissions.  
   - Models tested:  
     - `Ridge`  
     - `Lasso`  
     - `KNeighborsRegressor`  
     - `LinearRegression`  
     - `XGBRegressor`  
     - `RandomForestRegressor`  

5. **Results 📊**  
   - Performance comparison of models with and without the **ENERGYSTARScore** indicator.  
   - Best-performing models identified:  
     - `XGBRegressor`  
     - `RandomForestRegressor`  

6. **Impact of ENERGYSTARScore ⚡**  
   - Influence on the prediction of:  
     - Total energy consumption.  
     - CO2 emissions.  

7. **Conclusion and Areas for Improvement 🚀**  
   - Prediction results.  
   - Importance of model parameter optimization to enhance performance.  

---

## Overall Objective 🎯  
This project covers the full process of **data collection**, **cleaning**, **analysis**, and **modeling** to predict building energy consumption and CO2 emissions.  

## Technologies Used 💻  
- **Python**: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, XGBoost.  
- **Jupyter Notebook** for interactive analysis.  

---

# Analyse de la consommation énergétique des bâtiments de Seattle 🏢💡

Ce projet se concentre sur l'analyse et la modélisation des données de consommation énergétique des bâtiments de Seattle pour les années 2015 et 2016.

## Points clés 📝

1. **Contexte et présentation du jeu de données**  
   - Données de consommation énergétique des bâtiments de Seattle.  
   - Détails sur la taille des données, les valeurs nulles et non-nulles.

2. **Nettoyage et prétraitement des données 🧹**  
   - Filtrage des colonnes avec un pourcentage élevé de valeurs nulles.  
   - Gestion des doublons et des valeurs aberrantes.  

3. **Analyse exploratoire des données (EDA) 🔍**  
   - Analyse univariée et bivariée des données.  
   - Identification des corrélations entre les variables.  

4. **Modélisation 🧠**  
   - Création de modèles prédictifs pour :  
     - La consommation énergétique totale.  
     - Les émissions de CO2.  
   - Modèles testés :  
     - `Ridge`  
     - `Lasso`  
     - `KNeighborsRegressor`  
     - `LinearRegression`  
     - `XGBRegressor`  
     - `RandomForestRegressor`  

5. **Résultats 📊**  
   - Comparaison des performances des modèles avec et sans l'indicateur **ENERGYSTARScore**.  
   - Modèles les plus performants identifiés :  
     - `XGBRegressor`  
     - `RandomForestRegressor`  

6. **Impact de l'ENERGYSTARScore ⚡**  
   - Influence sur la prédiction de :  
     - La consommation énergétique totale.  
     - Les émissions de CO2.  

7. **Conclusion et pistes d'amélioration 🚀**  
   - Résultats des prédictions.  
   - Importance de l'optimisation des paramètres des modèles pour améliorer les performances.  

---

## Objectif global 🎯  
Ce projet couvre l'ensemble du processus de **collecte**, **nettoyage**, **analyse** et **modélisation** pour prédire la consommation énergétique des bâtiments et les émissions de CO2.  

## Technologies utilisées 💻  
- **Python** : Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, XGBoost.  
- **Jupyter Notebook** pour une analyse interactive.
