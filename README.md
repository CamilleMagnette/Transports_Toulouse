# 🚌 🚲 🚗 Transports_Toulouse

Il s'agit ici du résultat du 3ème projet mené pendant ma formation à la Wild Code School.


## 🎯 Objectif du projet :

Récupérer des données open data auprès de sociétés de transports (publiques ou privées) et faire une proposition d'application utilisateurs. 


## 🔎 Sources des données :  

- Parkings : [API data.toulouse-métropole.fr](https://data.toulouse-metropole.fr/pages/accueil/)   
Fichiers csv sources parkings relais et indigo

- Stations vélôToulouse : [API transport.data.gouv.fr](https://transport.data.gouv.fr/)  
Fichier Json disponibilité en temps réel 

- Stations bus, metro, tram : [API tisseo.fr](https://api.tisseo.fr/)   
Fichier Json arrêts et horaires en temps réel 


## 📎 Méthodologie technique :

1) Récupération et nettoyage des données auprès des API ciblées

2) Consolidation et préparation des données pour la création de l'application utilisateur

3) Mise en place de l'application utilisateur avec Dash

<img src="https://github.com/CamilleMagnette/Transports_Toulouse/blob/main/images/etapes.png" width=70% height=70%>


## ✅ Etapes : 

#### Semaine 1 :  
Appropriation et première exploration des données     
Outils principaux : Pandas, Matplotlib, jupyterLab   

[LIEN DIAGRAMME DE RETRAVAIL DES TABLES 💪 🕺](https://drive.google.com/file/d/17TfOcP2BalAt5omnFj4_L5hGJK4bfPqt/view?usp=sharing)

#### Semaines 2 et 3 : 
Jointures, filtres, nettoyage, recherche de corrélation     
Outils principaux : Pandas, Seaborn, DataPane, jupyterLab

[LIEN ANALYSE DES DONNEES SOUS DATAPANE 💡 📊](https://cloud.datapane.com/reports/VkGQlN3/exploration-des-donn%C3%A9es/)



4) [Tests de machine learning](http://localhost:8891/lab/tree/Documents/FORMATION%20DATA%20ANALYST/COURS%20DATA%20ANALYST/PROJET%202/JUPITERLAB%20NOTEBOOKS/Projet%202%20-%20Machine%20learning%20TEST%20ACTEURS.ipynb) : normalisation des données et mise en place d'un algorithme basé sur les plus proches voisins (algorithme K-nearest neighbors (kNN))
