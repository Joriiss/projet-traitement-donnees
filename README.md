# Projet d'Analyse et Prédiction de Marchés Financiers

## 📊 Rapport Complet
**Consultez le rapport détaillé :** [Projet Analyse et Prédiction de Marchés Financiers](https://www.notion.so/Projet-Analyse-et-Pr-diction-de-March-s-Financiers-28f516378a7780518d5ec2ef7c3c418a?source=copy_link)

## 🎯 Objectif du Projet

Ce projet vise à analyser et prédire les mouvements du marché financier français (CAC40) en utilisant des techniques d'analyse de données, de détection d'anomalies et d'apprentissage automatique.

### Objectifs Spécifiques

1. **Exploration et Nettoyage des Données**
   - Analyse des données historiques du CAC40
   - Identification et suppression des anomalies
   - Préparation des données pour l'analyse

2. **Détection d'Anomalies**
   - Application de méthodes statistiques (Z-Score, IQR)
   - Détection des valeurs aberrantes dans les données financières
   - Nettoyage et export des données sans anomalies

3. **Analyse Statistique**
   - Calcul d'indicateurs techniques (moyennes mobiles, momentum)
   - Implémentation d'un système de prédiction basé sur des règles
   - Évaluation de la performance des prédictions

4. **Prédiction par Machine Learning**
   - Création d'indicateurs techniques avancés
   - Développement d'un modèle Random Forest
   - Comparaison des prédictions avec les données réelles

## 📁 Structure du Projet

```
projet/
├── 01_data_exploration_cleaning.ipynb    # Exploration et nettoyage des données
├── 02_anomaly_detection.ipynb            # Détection d'anomalies
├── 03_statistical_analysis.ipynb         # Analyse statistique et prédictions basées sur des règles
├── 04_ml_prediction.ipynb                # Prédiction par machine learning
├── cac40.csv                             # Données originales du CAC40
├── cac40_cleaned.parquet                 # Données nettoyées
├── cac40_clean_no_anomalies.parquet      # Données sans anomalies
├── cac40_enriched_analysis.parquet       # Données enrichies avec indicateurs techniques
├── cac40_price_predictions.csv           # Prédictions basées sur des règles
├── cac40_ml_predictions.csv              # Prédictions par machine learning
└── README.md                             # Ce fichier
```

## 🔧 Technologies Utilisées

- **Python** : Langage de programmation principal
- **Pandas** : Manipulation et analyse des données
- **NumPy** : Calculs numériques
- **Matplotlib/Seaborn** : Visualisation des données
- **Scikit-learn** : Machine learning et prédiction
- **Jupyter Notebook** : Environnement de développement

## 📈 Méthodologie

### 1. Exploration des Données
- Analyse des données historiques du CAC40
- Identification des patterns et tendances
- Nettoyage des données manquantes ou erronées

### 2. Détection d'Anomalies
- **Z-Score** : Détection des valeurs statistiquement aberrantes
- **IQR (Interquartile Range)** : Identification des outliers
- **Déviation de la moyenne mobile** : Détection des écarts significatifs
- **Divergence STOXX** : Comparaison avec l'indice de référence

### 3. Analyse Statistique
- **Moyennes Mobiles** : MA_10, MA_20 pour identifier les tendances
- **Momentum** : Calcul de l'élan des prix
- **Prédictions Basées sur des Règles** : Système de trading automatisé

### 4. Machine Learning
- **Indicateurs Techniques** : MA_5, EMA_5, ROC_5, Volatilité, etc.
- **Random Forest** : Modèle de classification pour prédire la direction des prix
- **Évaluation** : Mesure de la performance du modèle

## 📊 Résultats Principaux

- **Détection d'Anomalies** : Identification et suppression des valeurs aberrantes
- **Prédictions Basées sur des Règles** : Système de trading avec règles techniques
- **Modèle ML** : Random Forest pour prédire les mouvements de prix
- **Visualisations** : Graphiques de performance et comparaisons

## 🚀 Utilisation

1. **Exécution des Notebooks** : Lancez les notebooks dans l'ordre (01 → 02 → 03 → 04)
2. **Données Requises** : Assurez-vous d'avoir le fichier `cac40.csv` dans le répertoire
3. **Dépendances** : Installez les packages Python requis (pandas, numpy, matplotlib, scikit-learn, etc.)

## 📝 Fichiers de Sortie

- **Données Nettoyées** : `cac40_clean_no_anomalies.parquet`
- **Données Enrichies** : `cac40_enriched_analysis.parquet`
- **Prédictions Règles** : `cac40_price_predictions.csv`
- **Prédictions ML** : `cac40_ml_predictions.csv`
