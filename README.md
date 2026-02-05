Projet d'Analyse de Données : Note globale et Régularité des Animés
__________________________________________________________________________________________________
Ce projet a été réalisé dans le cadre d'un Bachelor Développement Web. L'objectif est de dépasser la simple "note moyenne" pour évaluer la qualité réelle et la fiabilité éditoriale d'un catalogue d'animés grâce à la Data Science.

 Objectifs & Hypothèses
 __________________________________________________________________________________________________
L'analyse repose sur la validation de quatre hypothèses clés pour une prise de décision robuste :

H1 : La note globale seule est insuffisante. Deux animés avec la même moyenne peuvent offrir des expériences très différentes.

H2 : La régularité est un facteur clé. Un animé sans épisodes "faibles" est considéré comme "éditorialement sûr".

H3 : Un score composite simple. Création d'un indice reflétant mieux la qualité réelle qu'une simple note brute.

H4 : Décision robuste. Utilisation de ces scores pour justifier la mise en avant d'un contenu.

Fonctionnalités du Projet
___________________________________________________________________________________________________

Nettoyage de données : Suppression des doublons et traitement des valeurs manquantes (notamment pour la colonne Comm_Saison_3).

Ingénierie de variables (Feature Engineering) :

Calcul de l'Écart (Note Max - Note Min des épisodes).

Création du Score de Régularité (Base 10).

Visualisations de données :
__________________________________________________________________________________________________

Histogrammes : Distribution des notes avec focus sur les extrêmes.

Scatter Plots : Relation entre la Note Globale et la Régularité.

Bar Charts : Analyse de la répartition par Statut (Fini, En cours, etc.).

 Aperçu des Résultats
Le projet utilise la bibliothèque Matplotlib pour transformer les données brutes en informations visuelles :

Distribution des notes : Identification visuelle de la "moyenne" du catalogue.

Analyse de corrélation : Vérification mathématique du lien entre un "épisode de génie" et la note globale de la série.

 Technologies Utilisées
 ________________________________________________________________________________________________
Langage : Python 3.x

Bibliothèques : * Pandas (Manipulation et correction des données).

Matplotlib (Visualisations graphiques).

Outils : Jupyter Notebook / VS Code.

Structure des Fichiers
_____________________________________________________________________________________________
animes.csv : Le jeu de données initial.

projet_anime_data.ipynb : Le notebook contenant l'intégralité du code et des corrections.

README.md : Documentation du projet.

Installation
_________________________________________________________________________________________________
Installez les dépendances nécessaires :

Terminal:
pip install pandas matplotlib
Lancez le notebook dans votre environnement favori (VS Code ou Jupyter).

VScode Extension:Python jupyter


Auteur : Nassima ADLI

