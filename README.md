# RoadTrafficForecasting
Few R codes of my work as inter (report available on website link, only in french)


Seule une partie des travaux du stage est disponible ici.

Etapes à suivre:

1)Télécharger la library "markdown" pour lire les fichier .rmd

2)Aller sur "http://www.midaco-solver.com/index.php/download" pour télécharger l'extension de l'algo CACO.
Changer le nom du fichier dans "ACO.rmd" si necessaire.
Mettre l'extension dans le workspace

3)Explication des fichiers:
-"import data": permet d'importer les données des 3 base de données depuis les 3 fichiers excel (Urban_Matrix,
Chevire_Matrix, Bellevue_Matrix). Ici seulement la base de données Bellevue est disponible.
-"BellevueGeneralisationSEstimé": estimations des tailles de mémoire S sur Bellevue et création d'autres fonctions utilisées dans d'autres fichiers R
-"ACO": estimations des paramètres SVR avec l'algo d'optimisation des fourmis (CACO)
-"ONLINE CACO-SVR": algorithme de prévision avec online-SVR (permettant de fournir les prévisions et notamment les fichiers RData que l'on retrouve dans le fichier RData) et autres fonctions. Les fichiers RData ne sont pas disponibles ici.
-"comparaison_...": permet de comparer les modèles. Importation des données depuis les prévisions de vitesses au début. Données des autres méthodes de prévisions non disponibles ici
