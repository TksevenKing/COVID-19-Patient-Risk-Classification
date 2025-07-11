# 🦠 COVID-19 Patient Risk Classification with Machine Learning

![Python](https://img.shields.io/badge/Python-3.8%2B-blue?logo=python)
![scikit-learn](https://img.shields.io/badge/ML-scikit--learn-orange?logo=scikit-learn)
![License](https://img.shields.io/badge/License-MIT-green)

## 📌 Description

Ce projet de machine learning a pour objectif de prédire si un patient est **à risque** ou **non** de complications liées à la COVID-19, à partir de données médicales anonymisées.

Le modèle de classification est entraîné sur un sous-ensemble de données après nettoyage, transformation des variables catégorielles et normalisation. Les algorithmes explorés incluent :
- **Régression Logistique**
- **K-Nearest Neighbors (KNN)**
- **SVM (Support Vector Machine)**

Les performances sont évaluées avec **GridSearchCV**, **F1-score**, **accuracy**, et **rapport de classification**.

---

📊 Données utilisées
Les données sont issues d’un jeu de données public concernant les cas de COVID-19. Elles comprennent des variables comme :

Sexe

Pneumonie

Diabète

Hypertension

Obésité

Type de patient

Intubation, entrée en soins intensifs, décès

Statut de grossesse, tabagisme, maladies chroniques, etc.

Les colonnes avec des valeurs invalides (97, 99, "9999-99-99") ont été filtrées ou encodées.


