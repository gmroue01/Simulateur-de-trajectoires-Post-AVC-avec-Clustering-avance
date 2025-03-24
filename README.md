# projet_IG_BA3
Projet_IG_BA3 : Simulateur de trajectoires Post-AVC avec Clustering avancé
Ce github a pour objectif de repertorier l'ensemble des résultats relatif au projet.

Les différents résultats sont repartis tel que :

- Imputation --> ./Impute/imputation.ipynb  

    Résultats (à la dernière cellule) :
    - RMSE
    - Distance Wasserstein

- Génération synthétique --> ./Synthetic_Data_Generation/synthetic_data.ipynb

  - Kolmogorov-Smirnov
  - WasserStein
  - Cramèr's V
  - Evaluation sur un modèle de classification (AUC Score)
  - Novelty Detection
  - Anomaly Detection
  - PCA
  - Comparaison statistiques des données réelles et synthétiques (Mean,Median,Skewness,Kurtosis)
  - Comparaison des matrices de corrélations ( RMSE, Frobenius Norm)
  - Comparaison visuelles des matrices correlations (heatmap)
- Clustering --> ./Clustering/clustering.ipynb
     - K-Means
     - K-Prototype
     - Fuzzy Means
     - GPBOOST
     - GaussianMixture
     - DBSCAN
     - HDBSCAN
     - OPTICS
     - Spectral Clustering
     - Self-Organizing Map
     - AgglomerativeClustering
     - BIRCH
- Aucun résultats d'évaluations de clustering ne sont présenté pour l'instant
    
