# QRT-Grand-Data-Challenge
Hackathon de 8 jours organisé par QRT. En concurrence avec 200 étudiants de X, CS, ENSAE et Mines Paris (principalement en dernière année), j'ai atteint la 31ème place. 

## Objectif

L'objectif était de développer un modèle de **classification** pour prédire s'il fallait short des actifs d'un portfolio à partir de données synthétiques. La métrique d'évaluation était l' **accuracy**.

## Démarche et Modèles

L'analyse complète (EDA), le feature engineering et l'entraînement sont disponibles dans le notebook.

1.  **Analyse Exploratoire (EDA)** : Analyse de la distribution de la variable cible (classes relativement équilibrées) et des features. Analyse des tendances des signaux par décile. Utilisation de PCA. Détection et suppression des signaux bruités. Création de beaucoup de features.
2.  **Modélisation & Comparaison** :
    * `LogisticRegression`
    * `RandomForestClassifier`, `XGB`, `LGBM` (enlevé du notebook car moins performants ici)
  
## Technologies Utilisées

* Python
* Pandas & Numpy
* Scikit-learn (RandomForestClassifier, LogisticRegression, train_test_split, ...)
* Matplotlib & Seaborn

