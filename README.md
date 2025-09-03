# 📊 Analyse des Tendances YouTube

![Python](https://img.shields.io/badge/Python-3.9+-blue?logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-Scientific%20Computing-013243?logo=numpy&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-Data%20Viz-2E4C6D?logo=python&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-Interactive%20Viz-3F4F75?logo=plotly&logoColor=white)
![NLTK](https://img.shields.io/badge/NLTK-Sentiment%20Analysis-85C1E9?logo=python&logoColor=white)

---

## 🎯 Objectif du Projet
Projet d'analyse de données visant à **identifier les facteurs de performance** des vidéos tendances sur **YouTube**.  
L'objectif est d’aller **au-delà des métriques brutes** pour comprendre les véritables **drivers d'engagement**, en corrélant :  
- Le **contenu**  
- Le **sentiment des audiences**  
- La **présentation des vidéos**

---

## 🛠️ Méthodologie & Stack Technologique

### **1. Nettoyage & Feature Engineering** *(Python, Pandas, NumPy)*
- Création de métriques **normalisées** : `like_rate`, `comment_rate`.
- Préparation des données pour une **analyse comparative équitable**.

### **2. Analyse Statistique & Visualisation** *(Seaborn, Plotly)*
- **Boxplots** → comparaison de l’engagement par catégorie.
- **Heatmaps** → identification des corrélations entre variables.
- **Histogrammes** → analyse de la répartition des vues, likes et commentaires.

### **3. Analyse de Sentiment** *(NLTK VADER)*
- Traitement de **centaines de milliers de commentaires**.
- Classification automatique : *positif*, *neutre*, *négatif*.
- Génération de **nuages de mots** pour visualiser les thèmes dominants.

### **4. Analyse Textuelle**
- Étude de l’impact de la **ponctuation** et des **émojis** dans les titres.
- Évaluation de leur influence sur l’engagement des utilisateurs.

---

## 📈 Principaux Insights & Résultats

- 🎵 **Les catégories Musique & Humour** surperforment avec un **like_rate** significativement plus élevé.
- ❤️ Corrélation forte entre l’usage de certains **émojis** (*❤️, 😂*) et le **sentiment positif** des commentaires.
- ✍️ Découverte d’un **"point optimal"** : environ **6 signes de ponctuation** dans les titres → **engagement maximal**.
- 📺 Les chaînes **les plus actives** (talk-shows quotidiens) dominent le **classement des tendances**.

---

## 💡 Soft Skills Démontrées

- **Analyse Critique** & **Résolution de Problèmes Complexes**
- **Data Storytelling** : transformer les données en **insights actionnables**
- **Communication Visuelle** & **Valorisation des Résultats**


