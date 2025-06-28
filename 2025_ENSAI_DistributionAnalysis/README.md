# Objectifs du projet
## Objectif principal
Analyser les facteurs influençant le prix des maisons à Ames (Iowa, USA) à partir du dataset "Ames Housing". Construire et évaluer des modèles prédictifs pour estimer les prix immobiliers.

## Intérêt pédagogique
- Pratique de l'analyse exploratoire de données (EDA)
- Mise en œuvre de régressions linéaires et d'arbres de décision
- Validation des hypothèses statistiques
- Interprétation des résultats en contexte réel


# Structure du projet
project/
│
├── data/
│ ├── AmesHousing.csv # Données brutes
│
├── notebooks/
│ ├── .ipynb # Nettoyage des données
│
├── src/
│
└── outputs/ # Visualisations sauvegardées
│ ├── Loi de distribution de SalePrice.png
└─└── Ajustement d'une Log-normale à SalePrice.png


# Jeu de données

**Source**: [Kaggle - Ames Housing Dataset](https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data)

**Caractéristiques principales**:
- 2930 observations (maisons)
- Variable cible: `SalePrice` (prix de vente)


# Méthodologie
1. **Importation des bibliothèques**
    - Importation des bibliothèques

2. **Importation des données**
    - Importation des données

3. **Définition du cadre**
   - Etude descriptives de la variable cible
   - Recherche de la nature de la loi de distribution

4. **Etude de la variable d'intérêt**
   - Estimation des paramètres
   - Biais et EQM des estimateurs
   - Convergences et consistances des estimateurs

