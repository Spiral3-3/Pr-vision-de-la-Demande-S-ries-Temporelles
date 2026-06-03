# 📈 Prévision de la Demande — Séries Temporelles

> **Modélisation et prédiction des ventes futures à l'aide de modèles temporels et d'algorithmes de machine learning pour optimiser la gestion des stocks.**

## 🎯 Contexte et Objectif
L'objectif principal de ce projet est de modéliser et de prédire les ventes futures d'une chaîne de distribution afin d'optimiser la gestion des stocks. À partir d'un historique de ventes consolidé, le but est de construire un modèle robuste capable de générer des prévisions de ventes précises sur un horizon de **3 mois**, permettant ainsi d'anticiper la demande.

## 📊 Les Données
L'analyse repose sur un jeu de données structuré regroupant **5 années d'historique de ventes quotidiennes**. Ces données couvrent une granularité fine, incluant la distribution de :
- **50 articles différents** 📦
- Répartis à travers **10 magasins** 🏪

## 🚀 Défis Techniques et Approche
Ce projet permet d'explorer en profondeur les techniques d'analyse de séries temporelles et de Machine Learning appliquées à la prévision (*Forecasting*). La modélisation implique de répondre à plusieurs problématiques clés :

- **Gestion de la saisonnalité et des tendances :** Identifier et extraire les motifs récurrents (effets jours de la semaine, pics annuels, etc.) pour chaque produit.
- **Stratégie de modélisation :** Déterminer l'approche la plus performante entre la création de modèles indépendants pour chaque magasin/article, ou la mutualisation des données (*pooling*) pour dégager des comportements globaux.
- **Choix et comparaison des algorithmes :** Implémentation et évaluation de différentes méthodes afin d'obtenir la meilleure précision possible, allant des approches statistiques classiques aux algorithmes d'apprentissage automatique.

## 🛠️ Technologies Utilisées
- **Langage :** Python
- **Modélisation :** ARIMA, Machine Learning
- **Bibliothèques :** Scikit-Learn, Pandas, NumPy
- **Concepts :** Séries Temporelles (Time Series), Forecasting
