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

- Exploration et nettoyage des datasets : Google colab - Deepnote

- Librairies Python : Pandas - Folium – Plotly Express - Geopy

- Application utilisateurs  et solution d’hébergement : Dash – GitHub - Render

- Présentation projet : Power Point


## ✅ Etapes : 

<img src="https://github.com/CamilleMagnette/Transports_Toulouse/blob/main/images/etapes.png" width=70% height=70%>

1) Récupération et nettoyage des données auprès des API ciblées : [Notebook parkings](https://github.com/CamilleMagnette/Transports_Toulouse/blob/main/notebooks/Code_consolide%CC%81_pour_DASH_TISSEO.ipynb) / [Notebook velos](https://github.com/CamilleMagnette/Transports_Toulouse/blob/main/notebooks/Code_consolide%CC%81_pour_DASH_velos.ipynb) / 
 [Notebook tisseo](https://github.com/CamilleMagnette/Transports_Toulouse/blob/main/notebooks/Code_consolide%CC%81_pour_DASH_TISSEO.ipynb)   
2) Consolidation, préparation des données et mise en place de l'application utilisateur avec Dash : [Notebook Dash](https://github.com/CamilleMagnette/Transports_Toulouse/blob/main/app.py)


[🌸 PLATEFORME UTILISATEURS 🌸](https://transports-toulouse.onrender.com/)
