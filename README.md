Thibaut Cressent
# README Projet 9

## 1. Description générale du projet

Le dossier que vous venez d’ouvrir contient les livrables répondant aux attentes du projet 9 de la formation de Data Analyst : Produisez une étude de marché avec R ou Python.

Le travail est composé de trois notebooks fonctionnant dans l'ordre croissant :
- Projet 9.1 : nettoyage et jointure des fichiers.ipynb
- Projet 9.2 : analyses univariées et bivariées.ipynb
- Projet 9.3 : ACP, K-means & CAH.ipynb

## 2. Configuration du développeur

Version de Python utilisée : 3.7.13

Environnement de développement : Google Colaboratory

Version de l’OS : Windows 10

## 3. Installation du programme
Le premier notebook “nettoyage et jointure des fichiers” nécessite l’installation préalable des fichiers CSV fournis dans le projet :
- DisponibiliteAlimentaire_2017.csv
- Population_2000_2018.csv

Ce notebook inclus aussi l'importation de 12 fichiers supplémentaires, extraits du site de la FAO ou créés par mes soins. Ces fichiers sont importés dans le notebook directement depuis ma page GitHub et ne nécessitent donc aucune importation.

Par la suite, le second notebook “analyses univariées et bivariées” et le troisième 'ACP, K-means & CAH" requierent l’exportation du premier notebook "df_complet.csv", commande située en fin de fichier.

Cependant, pour éviter toute complication à l'importation, le fichier df_complet.csv est également disponible sur GitHub et est directement importé sur les autres notebooks via le lien permalink.


## 4. Fonctionnalités

Le premier notebook a pour objectif de :
-	comprendre le fonctionnement de notre premier jeu de données (Disponibilité Alimentaire & Population) : quelles informations fonctionnelles apportent-elles? Que représentent une ligne, une colonne? Comment améliorer le modèle ?  transformation en table pivot
-	recueillir les données supplémentaires que je souhaite ajouter à mes travaux
-	nettoyer ces 14 fichiers (traitement des doublons, traitement des valeurs manquantes en fonction des données, …)
-	joindre tous nos fichiers simultanément
-	Exporter notre nouveau dataframe

Le second notebook a quant à lui pour objectif de répondre à toutes les questions posées par l’exploration descriptive. Vous y trouverez :
-	 Traitement basique du dataframe
-	Analyse uni-variée (aperçu des données, étude de la distribution, des valeurs via boxplot, et inspection des valeurs extrêmes)
-	Analyse bi-variée (étude de possibles corrélations entre nos différentes variables, …)

Enfin, le 3ème notebook répondra à la problématique de départ : produire une étude de marché. Ce travail se divise en plusieurs étapes : l’application de la méthode ACP pour réduction de dimension, clustering avec K-Means et CAH, analyse, interprétation des résultats et recommandations.
