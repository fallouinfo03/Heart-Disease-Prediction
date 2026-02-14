# Heart-Disease-Prediction
Projet de prédiction des maladies cardiaques avec Python et Scikit-Learn.
# 🫀 Prédiction des Maladies Cardiovasculaires

![Python](https://img.shields.io/badge/Python-3.9%2B-blue)
![Scikit-Learn](https://img.shields.io/badge/Library-Scikit--Learn-orange)

Ce projet a été réalisé dans le cadre du cours d'**IA appliquée au Prétraitement des données**. L'objectif était de concevoir un pipeline de machine learning pour prédire les maladies cardiovasculaires.

##  Description
Le projet exploite le dataset **Heart Disease UCI**. Il contient des données avec beaucoup de valeurs manquantes, nécessitant un nettoyage rigoureux.

##  Méthodologie (Pipeline)
1.  **Imputation** : KNNImputer pour les valeurs numériques manquantes.
2.  **Encodage** : OneHotEncoder (variables nominales) et OrdinalEncoder (variables ordinales).
3.  **Feature Engineering** : Discrétisation de l'âge et création de variables polynomiales.
4.  **Modèle** : RandomForestClassifier (Accuracy ~80%).

##  Contenu
* `Notebook_Traitement.ipynb` : Le code complet.
* `Rapport_Technique.pdf` : Les explications détaillées.
* `heart_disease_uci.csv` : Les données.

##  Auteurs
* **Wissal Akkaoui**
* **Serigne Fallou Mbacke**
* **Ahossan Marc Cedrick Tanoh**
