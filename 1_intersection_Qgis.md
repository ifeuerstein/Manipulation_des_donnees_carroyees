# Interpolation entre des données Insee et un fond de carte

Qgis (3.14 Pi) permet de faire facilement l'interpolation entre une couche carroyée et un fond de carte. L'ouverture des couches de carreaux (paris.shp) et des quartiers de la politique de la ville s'effectue à l'aide du menu *Couche/ajouter une couche/Ajouter une couche vecteur*.

L'interpolation et l'agrégation peuvent être réalisées directement à l'aide de la fonction *Joindre les attributs par localisation (résumé)* (à ne pas confondre avec la fonction soeur contenue dans le menu *Vecteur*) contenue dans le menu *Boite à outils de traitements/Outils généraux pour les vecteurs*.

![image info](/images/inter1.png)

Dans le champs *Résumés à calculer* cocher uniquement *somme* pour obtenir des totaux.

Vous obtenez une couche temporaire avec le résultat escompté :


Il ne reste plus qu'à l'enregistrer en *hapefile* en opérant un clic droit sur le nom de la couche dans la fenêtre couches puis à choisir *Exporter/Sauvegarder les entités sous*. En sauvegardant en *shapefile* (.shp) vous obtiendrez un fichier .dbf que vous pourrez ouvrir sous un logiciel statistique pour réaliser l'agrégation.
