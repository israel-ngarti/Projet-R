# 📊 Analyse croisée des brevets et des offres d'emploi en Data Science

Projet de traitement et d’analyse de données en R réalisé dans le cadre du cours *Introduction à la programmation en R* – M1 ROAD & M1 IREF, Automne 2024.

## 🎯 Objectif

L’objectif de ce projet est d’explorer le lien entre l’innovation des entreprises (mesurée par les brevets) et leur demande en compétences (données issues des offres d’emploi).  
Quelques questions abordées :
- Les entreprises les plus innovantes paient-elles mieux ?
- Demandent-elles plus souvent des compétences en machine learning ?
- Y a-t-il des secteurs ou codes IPCs particulièrement liés à la demande en data science ?

---

## 🛠️ Méthodologie

### 📁 Traitement des données

- **Base de brevets (`base_brevets`)**
  - Créée à partir de données brutes issues de l’OCDE et de la classification IPC
  - Variables : nombre de brevets, ville/département, codes IPC principaux, etc.
  - Filtrage sur les entreprises françaises, période 2010–2020

- **Base d’offres d’emploi (`base_emp`)**
  - Créée à partir de données webscrappées d’annonces de data scientists
  - Variables : entreprise, salaire moyen, compétence la plus demandée, secteur, expérience, etc.

- **Appariement (`base_emp_inno`)**
  - Fusion des deux bases par le nom d’entreprise
  - Objectif : relier innovation et demande de compétences

---

## 📈 Résultats

Les résultats sont présentés sur un **site web hébergé sur GitHub Pages** comprenant :
- Une **page d’accueil** avec les infos du projet et des membres du groupe
- Une page dédiée aux **statistiques descriptives**
- Une page dédiée à l’**analyse exploratoire et visualisations**

Les statistiques comprennent : moyenne, médiane, min, max, écart-type, top 5 entreprises par brevets/salaires, etc.

---

## 🧪 Technologies utilisées

- **Langage :** R
- **Packages principaux :** `data.table`, `ggplot2`, `stringr`, `quarto`
- **Visualisation :** ggplot2, wordclouds, graphiques interactifs
- **Hébergement du site :** GitHub Pages avec Quarto

---

## 👨‍👩‍👧‍👦 Membres du groupe

- MOIELWAY NGARTI Israël
- BARKIRE DOURAMANE
- KARAMA FABARIKA
- Ismaïl ZAROQ

---


