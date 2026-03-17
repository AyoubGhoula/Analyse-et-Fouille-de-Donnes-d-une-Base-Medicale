# 🩺 Analyse et Fouille de Données d’une Base Médicale

## 📌 Description

Ce projet a pour objectif d’analyser et d’extraire des connaissances à partir d’une base de données médicale liée au cancer du poumon.

En utilisant des techniques de prétraitement, d’analyse statistique et de data mining, ce travail vise à aider à la prise de décision médicale en identifiant des patterns pertinents dans les données.

---

## 🎯 Contexte & Motivation

Selon l’Organisation Mondiale de la Santé (OMS), le cancer du poumon est l’une des principales causes de mortalité dans le monde.

Ce projet s’inscrit dans une démarche d’aide au diagnostic en proposant une approche basée sur l’analyse de données afin de faciliter l’identification précoce des cas à risque.

---

## 🎯 Objectifs

* Nettoyer et préparer les données médicales
* Analyser les relations entre les variables
* Réduire la dimensionnalité des données (ACP)
* Appliquer des méthodes de clustering
* Interpréter les résultats pour une aide à la décision

---

## 📂 Données

* Fichier utilisé : `cancer_des_poumons.csv`
* Contenu : informations sur des patients et leurs caractéristiques médicales

---

## ⚙️ Méthodologie

### 1️⃣ Préparation des données

* Chargement et exploration du dataset
* Gestion des valeurs manquantes (remplacement par la moyenne)
* Encodage des variables catégorielles
* Normalisation des données
* Analyse de corrélation

---

### 2️⃣ Extraction des caractéristiques (ACP)

* Application de l’Analyse en Composantes Principales (ACP)
* Étude des valeurs propres
* Analyse de l’inertie expliquée
* Visualisation (cercle de corrélation)

---

### 3️⃣ Data Mining

* 🔹 K-means (clustering en 2 classes)
* 🔹 Classification Ascendante Hiérarchique (CAH)
* Comparaison des résultats obtenus

---

### 4️⃣ Interface Graphique (Optionnelle)

Développement d’une interface en Python permettant :

* L’importation des données
* L’exécution des traitements
* La visualisation des résultats

---

## 🛠️ Technologies Utilisées

* Python 🐍
* Pandas (manipulation des données)
* NumPy
* Matplotlib / Seaborn (visualisation)
* Scikit-learn (ACP, K-means)
* Scipy (CAH)
* Tkinter / PyQt (interface graphique)

---

## ▶️ Exécution

1. Cloner le dépôt :

```bash
git clone https://github.com/your-username/medical-data-mining.git
cd medical-data-mining
```

2. Installer les dépendances :

```bash
pip install pandas numpy matplotlib seaborn scikit-learn scipy
```

3. Lancer le projet :

```bash
python main.py
```

---

## 📊 Résultats Attendus

* Identification des variables les plus influentes
* Réduction de dimension via ACP
* Classification des patients (malades / sains)
* Visualisations pour interprétation

---

## 📁 Structure du Projet

```bash
project/
│── data/
│   └── cancer_des_poumons.csv
│── src/
│   ├── preprocessing.py
│   ├── pca.py
│   ├── clustering.py
│   └── visualization.py
│── ui/
│── main.py
│── README.md
```

---



## 🚀 Améliorations Futures

* Intégration de modèles de Machine Learning supervisés
* Amélioration de l’interface utilisateur
* Déploiement sous forme d’application web
* Ajout de nouvelles sources de données

---

## 👨‍💻 Auteur

* Nom : Votre Nom
* GitHub : https://github.com/your-username
