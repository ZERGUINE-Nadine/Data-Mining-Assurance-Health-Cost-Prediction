# 📊 Data Mining – Assurance Health Cost Prediction

## 📌 Présentation
Ce projet a été réalisé dans le cadre d’un travail académique autour de la **data science et du data mining**.  
L’objectif est d’appliquer une **analyse exploratoire des données (EDA)** et d’implémenter un **algorithme de régression** permettant de prédire le **coût d’assurance santé** d’un individu en fonction de son profil.  

---

## 🗂️ Dataset
Le dataset est issu de données publiques du gouvernement américain. Il contient des informations sur les bénéficiaires d’assurance santé, avec les attributs suivants :  

- `age` : âge du bénéficiaire principal  
- `sex` : sexe (homme, femme)  
- `bmi` : indice de masse corporelle (kg/m²)  
- `children` : nombre d’enfants/personnes à charge  
- `smoker` : statut fumeur/non-fumeur  
- `region` : région de résidence (nord-est, sud-est, sud-ouest, nord-ouest)  
- `charges` : frais médicaux individuels facturés par l’assurance  

🎯 **Problématique** : prédire la variable cible `charges` à l’aide des autres attributs.  

---

## 🔎 Étapes du projet

### 1. **Exploration des données (EDA)**
- Nettoyage des données  
- Analyse statistique descriptive  
- Visualisations (distribution des variables, corrélations, boxplots, heatmaps, etc.)  
- Détection et traitement des outliers  

### 2. **Préparation des données**
- Encodage des variables catégorielles (`sex`, `smoker`, `region`)  
- Normalisation / standardisation des variables numériques  
- Séparation en **train/test split**  

### 3. **Modélisation**
- Implémentation de plusieurs modèles de **régression supervisée** :  
  - Régression linéaire  
  - Régression Ridge / Lasso  
  - Random Forest Regressor  

### 4. **Résultats**
- Comparaison des performances entre modèles  
- Interprétation des variables les plus influentes (importance des features)  
- Visualisation des prédictions vs valeurs réelles  

---

## ⚙️ Technologies utilisées
- **Langage** : Python  
- **Bibliothèques principales** :  
  - `pandas`, `numpy` → manipulation et préparation des données  
  - `matplotlib`, `seaborn` → visualisations  
  - `scikit-learn` → modélisation et évaluation des modèles  
  - `statsmodels` (optionnel) → analyse statistique  
  - `jupyter notebook` → développement et présentation du projet  

---

