<!-- Bannière -->
<div align="center">
  <img src="../assets/fewinfos-banner.png" alt="Bienvenue dans FEWINFOS Contribution - Widget de statistiques GitHub" width="100%">
</div>

# 📦 Widget de statistiques de dépôt GitHub

Outil **open-source**, entièrement côté client, qui visualise **les statistiques d’un dépôt GitHub en temps réel** dans un format interactif et personnalisable — idéal pour les développeurs, mainteneurs de projets open-source et portfolios.

---

## 🎯 Objectif

Ce widget utilise l’API REST de GitHub pour récupérer et afficher diverses métadonnées et analyses sur n’importe quel dépôt GitHub public.  
Il fonctionne **entièrement dans le navigateur** sans backend ni authentification.

---

## ✨ Fonctionnalités

- 🔄 Récupération des données en temps réel via l’API REST GitHub  
- ⭐ Affiche le nombre d’étoiles, forks, abonnés, issues ouvertes et fermées  
- 👥 Visualise les meilleurs contributeurs avec avatars et nombre de commits  
- 📊 Montre les langages utilisés avec graphiques interactifs  
- 📅 Affiche la date de création et la dernière mise à jour du dépôt  
- 📜 Affiche les informations de licence  
- 🎨 Interface propre, responsive et personnalisable  
- 💻 Fonctionne directement dans le navigateur (aucune configuration serveur)  
- 🧩 Facile à intégrer dans des sites web ou README.md  
- 📈 Visualisations supplémentaires avec Chart.js  

---

## 🧱 Technologies

- **HTML** – structure et balisage  
- **CSS** – styles et adaptabilité  
- **JavaScript** – logique et interaction avec l’API  
- **GitHub REST API** – source des données  
- **Chart.js** – pour la création de graphiques (optionnel)  

---

## 📊 Widgets disponibles

### 🔍 Statistiques du dépôt

- ⭐ Étoiles / 🍴 Forks / 👁️ Abonnés  
- 📅 Date de création et dernière mise à jour  
- 📜 Type de licence  
- 📊 Langages utilisés (camembert, histogramme, diagramme en anneau)  
- 📦 Graphe des dépendances (npm, pip, etc.)  
- 📈 Carte thermique de l’activité des commits  
- 🕐 Temps moyen de fusion des PR  
- 🧵 Répartition des issues (Ouvertes / Fermées / Épinglées)  

### 👥 Widgets de contributeurs

- 👥 Meilleurs contributeurs (avatar + commits)  
- 📊 Contributions par jour de la semaine  
- 🗺️ Carte des localisations des contributeurs (données publiques)  
- ⏱️ Contributeurs récents (7 / 30 derniers jours)  
- 📈 Contribution dans le temps (graphique cumulatif)  

### 📊 Widgets graphiques

- 📊 Diagramme radar de la « santé » du dépôt (étoiles, forks, PR, issues)  
- 📉 Courbe de croissance des étoiles/forks  
- 🍩 Diagramme en anneau de l’utilisation des langages  
- 📈 Graphique des tendances des issues/PR  
- 📆 Calendrier d’activité à la GitHub  

### ⚙️ DevOps et CI/CD

- 🚦 Badge de statut GitHub Actions CI/CD  
- 🧪 Badge de couverture de code (Codecov, Coveralls)  
- 🔄 Widget du dernier run de workflow  
- 🛠️ Historique des builds (succès/échecs)  

### 📌 Issues et PR

- 📋 Issues ou discussions épinglées  
- 🔍 Nuage de mots pour les labels d’issues  
- 📬 Tracker du statut/taux de fusion des PR  
- 📈 Indicateur de « sentiment » des issues (basé sur des mots-clés)  

### 🧩 Autres widgets

- 📌 Bouton « Mettre en favori »  
- 🔍 Recherche intégrée d’autres dépôts  
- 🧠 Résumé IA des commits (optionnel)  
- 🔗 Widget des dépôts liés  
- 🪄 Export en iframe / HTML  

---

## 📂 Structure du projet

github-repo-stats-widget/
├── index.html # Fichier HTML principal
├── style.css # Styles CSS
├── repo.js # Logique JavaScript
├── charts.js # Logique de génération des graphiques
├── assets/ # Icônes, captures d’écran
├── README.md # Ce fichier de documentation
└── LICENSE # Licence MIT

---

## 🚀 Déploiement

Vous pouvez déployer le widget sur **GitHub Pages** ou n’importe quel hébergeur statique (Netlify, Vercel, Firebase).

### Déploiement via GitHub Pages

1. Uploadez le projet sur GitHub  
2. Allez dans **Settings → Pages**  
3. Sélectionnez la branche : `main` et le dossier : `/ (root)`  
4. Votre widget sera accessible à l’adresse :  
   `https://votreutilisateur.github.io/github-repo-stats-widget/`
