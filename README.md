# Analyse de la consommation d'énergie des bâtiments de Seattle  

Ce projet se concentre sur l'analyse et la modélisation des données de consommation d'énergie des bâtiments de Seattle pour les années 2015 et 2016.  

## Thèmes principaux  

1. **Contexte et présentation des Data-Set**  
   - Données sur la consommation d'énergie des bâtiments de Seattle.  
   - Détails sur la taille des données, les valeurs nulles et non nulles.  

2. **Traitement et nettoyage des données**  
   - Filtration des colonnes avec un pourcentage élevé de valeurs nulles.  
   - Gestion des doublons et des valeurs aberrantes.  

3. **Analyse exploratoire**  
   - Analyse univariée et bivariée des données.  
   - Identification des corrélations entre les variables.  

4. **Modélisation**  
   - Création de modèles prédictifs pour :  
     - La consommation d'énergie totale.  
     - Les émissions de CO2.  
   - Modèles testés :  
     - `Ridge`  
     - `Lasso`  
     - `KNeighborsRegressor`  
     - `LinearRegression`  
     - `XGBRegressor`  
     - `RandomForestRegressor`  

5. **Résultats**  
   - Comparaison des performances des modèles avec et sans l'indicateur **ENERGYSTARScore**.  
   - Identification des meilleurs modèles :  
     - `XGBRegressor`  
     - `RandomForestRegressor`  

6. **Impact de l'ENERGYSTARScore**  
   - Influence sur la prédiction de :  
     - La consommation d'énergie totale.  
     - Les émissions de CO2.  

7. **Conclusion et axes d'amélioration**  
   - Résultats des prédictions.  
   - Importance de l'optimisation des paramètres des modèles pour améliorer leurs performances.  

## Objectif global  
Ces thèmes couvrent l'ensemble du processus de **collecte**, **nettoyage**, **analyse** et **modélisation des données** pour prédire la consommation d'énergie et les émissions de CO2 des bâtiments.  

## Technologies utilisées  
- Python : Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, XGBoost.  
- Jupyter Notebook pour l'analyse interactive.  

---
