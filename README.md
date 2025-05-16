<p align="center">
   <img src="https://www.asc-csa.gc.ca/images/recherche/tiles/50d50dc4-45c1-4933-8a41-b312472b3bb3.jpg" alt="SAR Imagery" height=300> 
   <br> Crédit d'image | Image credit: <a href=https://www.asc-csa.gc.ca/images/recherche/tiles>ASC-CSA</a>
</p>

<p align="center">
    <a href="#stars">
        <img alt="Étoiles sur GitHub | GitHub Repo stars" src="https://img.shields.io/github/stars/asc-csa/Synthetic_Aperture_Radar_Tutorial">
    </a>
    <a href="#watchers">
        <img alt="Spectateurs sur Github | GitHub watchers" src="https://img.shields.io/github/watchers/asc-csa/Synthetic_Aperture_Radar_Tutorial">
    </a>
    <a href="https://github.com/asc-csa/Synthetic_Aperture_Radar_Tutorial/commits/main">
        <img alt="Dernier commit sur GitHub | GitHub last commit" src="https://img.shields.io/github/last-commit/asc-csa/Synthetic_Aperture_Radar_Tutorial">
    </a>
    <a href="https://github.com/asc-csa/Synthetic_Aperture_Radar_Tutorial/graphs/contributors">
        <img alt="Contributeurs sur GitHub | GitHub contributors" src="https://img.shields.io/github/contributors/asc-csa/Synthetic_Aperture_Radar_Tutorial">
    </a>
    <a href="https://twitter.com/intent/follow?screen_name=csa_asc">
        <img alt="Suivre sur Twitter | Twitter Follow" src="https://img.shields.io/twitter/follow/csa_asc?style=social">
    </a>
</p>

<h2 align="center">
  <a href="#titre-du-projet">Français</a> |
  <a href="#project-title">English (follows)</a>
</h2>

<a id="titre-du-projet"></a>
# Radar à synthèse d'ouverture (RSO) - Un tutoriel 

> **Description brève :**
> Ce tutoriel, destiné aux débutants, montre étape par étape comment utiliser les données des missions RADARSAT en Python et QGIS pour tracer des fichiers raster et shapefiles.

---

# À propos
Le tutoriel suivant a été créé pour aider les utilisateurs à utiliser les données de mission RADARSAT. Ce tutoriel s’adresse aux débutants et offre un guide étape par étape pour guider les utilisateurs avec le traçage des fichiers raster et des fichiers de formes des missions RADARSAT en python et QGIS. 

## Démarrage rapide
Pour le Jupyter Notebook.
1. 📦 **Cloner le dépôt**
   ```bash
   git clone https://github.com/asc-csa/Synthetic_Aperture_Radar_Tutorial.git
   cd Synthetic_Aperture_Radar_Tutorial
   ```
2. 🐍 **Créer un environnement**
   ```bash
   # Avec virtualenv
   python -m venv env
   source env/bin/activate

   # Ou avec conda
   conda create -n sar_env
   conda activate sar_env
   ```
3. 📥 **Installer les dépendances**
   ```bash
   pip install -r requirements.txt
   ```
4. 🚀 **Lancer le tutoriel**
   ```bash
   jupyter notebook BC Wildfire raster plot.ipynb
   ```
> **Remarque :** Si les graphiques ou cartes ne s’affichent pas, redémarrez Jupyter Notebook ou ajoutez `%matplotlib inline` dans la première cellule.

## Fonctionnalités
Sur cette page se trouvent les deux dossiers suivants : 
*Option 1 - QGIS:
  1) Un fichier pdf avec un guide étape par étape sur l’utilisation de QGIS et le téléchargement d’un fichier raster et d’un fichier vectoriel.
  2) Un exemple de fichier raster tracé dans QGIS à partir de feux de forêt en Colombie-Britannique pris par RCM3 - OK2080033 (le lien se trouve ci-dessous). 
*Option 2 - Python:
  1) Le carnet de notes jupyter avec des exemples de traçage de fichiers raster via osgeo et cartopy. 
  
### Accès aux données:
- Le fichier raster est basé sur les données RCM tirées du lien suivant : https://donnees-data.asc-csa.gc.ca/users/OpenData_DonneesOuvertes/pub/BC%20fires/
- Le fichier de formes est tiré du lien suivant : http://www.naturalearthdata.com/features/

## Licence

Ce projet est  sous une licence MIT modifiée – voir le fichier [LICENSE](https://github.com/asc-csa/Synthetic_Aperture_Radar_Tutorial/blob/main/LICENSE.txt) pour plus de détails.

---

<h2 align="center">
  <a href="#project-title">English </a> |
  <a href="#titre-du-projet">Français (précède)</a>
</h2>

<a id="project-title"></a>
# Synthetic Aperture Radar (SAR) - A tutorial

> **Brief description:**
> This beginner-friendly tutorial provides a step-by-step guide on using RADARSAT mission data in Python and QGIS to plot raster files and shapefiles.


## About
The following tutorial was created to assist users with the usage of RADARSAT mission data. This tutorial is geared towards beginners and offers a step by step guide to direct users with plotting the raster files and shapefiles of RADARSAT missions in python and QGIS. 

## Quick Start
For the Jupyter Notebook. 
1. 📦 **Clone the repo**
   ```bash
   git clone https://github.com/asc-csa/Synthetic_Aperture_Radar_Tutorial.git
   cd Synthetic_Aperture_Radar_Tutorial
   ```
2. 🐍 **Create environment**
   ```bash
   # Using virtualenv
   python -m venv env
   source env/bin/activate

   # Or using conda
   conda create -n sar_env
   conda activate sar_env
   ```
3. 📥 **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```
4. 🚀 **Run the tutorial**
   ```bash
   jupyter notebook BC Wildfire raster plot.ipynb.ipynb
   ```
> **Note:** If plots or maps do not display, restart Jupyter Notebook or run `%matplotlib inline` in the first cell.

## Functionality
On this page the following two folders can be found: 
* Option 1 - QGIS:
  1) A file with a step by step guide on using QGIS and uploading a raster and a vector file.
  2) An example of a plotted raster file in QGIS from British Columbia wild fires taken by RCM3 - OK2080033 (The link can be found below).  
* Option 2 - Python: 
  1) The jupyter notebook with examples of plotting a raster files via osgeo and cartopy. 

### Data Access
- The raster file is based on the RCM data from the following link: https://donnees-data.asc-csa.gc.ca/users/OpenData_DonneesOuvertes/pub/BC%20fires/
- The shapefile is taken from the following link: http://www.naturalearthdata.com/features/

## License

This project is licensed under a modified MIT license - see the [LICENSE](https://github.com/asc-csa/Synthetic_Aperture_Radar_Tutorial/blob/main/LICENSE.txt) file for details.

---


        
  
