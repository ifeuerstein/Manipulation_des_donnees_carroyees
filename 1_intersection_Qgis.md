# Interpolation entre des données Insee et un fond de carte

Qgis (3.14 Pi) permet de faire facilement l'interpolation entre une couche carroyée et un fond de carte. L'ouverture des couches de carreaux (paris.shp) et des quartiers de la politique de la ville s'effectue à l'aide du menu *Couche\ajouter une couche\Ajouter une couche vecteur*.



Après avoir ouvert les deux fichiers (paris.shp et qp_bdtopo_com_75056_2020.shp) à l'aide du menu : , vous réalisez l'interpolation à l'aide de la commande 'Joindre les attributs par localisation' contenue dans le menu Vecteur\Outil de gestion des données.


Vous obtenez une nouvelle couche contenant à la fois des données provenant des carreaux et des quartiers de la politique de la ville.


Il reste à enregistrer ce fichier en Shapefile en effectuant un clique droit sur le nom de la couche dans la fenêtre couches puis à choisir 'Exporter\Sauvegarder les entités sous'. En sauvegardant en shapefile (.shp) vous obtiendrez un fichier .dbf que vous pourrez ouvrir sous un logiciel statistique pour réaliser l'agrégation.
