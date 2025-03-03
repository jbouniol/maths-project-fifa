# maths-project-fifa

## Projet d'Analyse en Composantes Principales (ACP) sur les Performances des Joueurs de Football

Ce projet applique des concepts mathématiques de réduction dimensionnelle (ACP/PCA) sur des données de joueurs de football européens pour analyser leurs performances.

### Objectifs
- Explorer et préparer les données de la European Soccer Database
- Appliquer l'Analyse en Composantes Principales (ACP)
- Réaliser une Décomposition en Valeurs Singulières (SVD)
- Visualiser et interpréter les résultats

### Méthodologie
1. **Exploration et préparation des données**
    - Analyse de structure (variables numériques/catégorielles)
    - Nettoyage (valeurs manquantes, outliers)
    - Gestion des variables catégorielles (encodage One-Hot)
    - Standardisation (Z-score)

2. **Analyse en Composantes Principales**
    - Construction de la matrice de corrélation
    - Détermination du nombre optimal de composantes
    - Visualisation du cercle de corrélation
    - Projection des joueurs sur le plan factoriel
    - Clustering sur les composantes principales

3. **Décomposition en Valeurs Singulières**
    - Application de la SVD sur la matrice normalisée
    - Comparaison avec les résultats de l'ACP

4. **Visualisation et interprétation**
    - Création de graphiques explicatifs
    - Interprétation des clusters de joueurs
    - Identification de profils-types pour chaque groupe

### Résultats attendus
- Identification des facteurs principaux expliquant les performances des joueurs
- Segmentation des joueurs selon leurs caractéristiques
- Analyse des corrélations entre les différentes statistiques de performance
- Recommandations potentielles pour les stratégies d'entraînement et de recrutement