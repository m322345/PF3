![Entete](images/projet.png)

# 📌 Anticipation des Besoins en Consommation des Bâtiments

## 📖 Contexte
La ville de **Seattle** souhaite atteindre un objectif de **neutralité carbone d’ici 2050**. Pour cela, une analyse approfondie de la **consommation énergétique et des émissions de CO₂** des bâtiments non résidentiels est nécessaire.

Les relevés de consommation étant coûteux, l’objectif est de développer un **modèle de prédiction** basé sur les caractéristiques structurelles des bâtiments (taille, usage, localisation, etc.). Le projet vise également à évaluer l’intérêt de l’**ENERGY STAR Score** comme variable prédictive.

## 🎯 Objectifs du Projet
- ✅ Analyser et nettoyer les données pour préparer la modélisation.
- ✅ Tester **plusieurs modèles de prédiction** pour la consommation énergétique et les émissions de CO₂.
- ✅ Optimiser le modèle en utilisant des **techniques de feature engineering et d’hyperparamétrisation**.
- ✅ Évaluer l’impact de l’**ENERGY STAR Score** sur les prédictions.

## 🛠️ Étapes du Projet

### 1️⃣ **Exploration et Préparation des Données**
- Comprendre et analyser la **structure des données**.
- Identification des **valeurs aberrantes, manquantes et incohérences**.
- Effectuer un premier **feature engineering** (normalisation, transformation des variables).

### 2️⃣ **Construction d’un Premier Modèle**
- Test d'une **régression linéaire** comme **baseline**.
- Mise en place d'une **validation croisée** pour éviter l’overfitting.
- Expérimentation avec des **méthodes d’ensemble** (Random Forest, Gradient Boosting, etc.).

### 3️⃣ **Optimisation et Sélection du Modèle**
- Amélioration des prédictions via **feature selection et engineering avancé**.
- Application d'une **PCA pour effectuer une réduction de dimensionnalité**.
- Sélection et optimisation du modèle final avec **Grid Search**.

### 4️⃣ **Interprétation et Explicabilité**
- Évaluation de l’importance des variables avec **SHAP**.
- Vérification de l’impact de l’**ENERGY STAR Score** sur les prédictions.
- Production de **visualisations claires** des résultats.

### 5️⃣ **Modélisation d’une Deuxième Target**
- Répétition des étapes précédentes pour prédire la **consommation énergétique totale**.
- Comparaison des performances des modèles appliqués aux deux cibles.

## 📦 Livrables Attendus
- ✅ Un **notebook** contenant l’analyse exploratoire et les résultats des tests de modélisation.
- ✅ Un **modèle de prédiction optimisé** pour les émissions de CO₂ et la consommation énergétique.
- ✅ Une **analyse détaillée de l’importance des variables**.
- ✅ Une **présentation expliquant la méthodologie et les conclusions**.

## 🚀 Objectif Final
Développer un **modèle fiable et interprétable** permettant de prédire la consommation et les émissions des bâtiments non résidentiels, afin d’aider la ville de **Seattle** à optimiser ses stratégies de réduction d’émissions.

---
- 👥 **Compétences requises** : Machine Learning, Feature Engineering, Sklearn, Python.
- 🌍 **Source des données** : [Relevés de consommation et caractéristiques des bâtiments de Seattle.](https://data.seattle.gov/Built-Environment/Building-Energy-Benchmarking-Data-2015-Present/teqw-tu6e/about_data)
