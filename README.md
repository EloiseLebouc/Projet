Projet
======

Ci dessous se trouvent les différentes commandes git utiles à la récupération des données.

Vous devez en tout premier installer GIT sur votre ordinateur, étant sur Ubuntu je ne sais pas trop comment ça fonctionne sous windows et je vous laisse donc vous débrouillez pour cette première partie.

Ensuite il vous faut cloner le dossier "Projet" que j'ai créé et sur lequel se trouvent maintenant toutes les données des mesures que nosu avons effectuées lors de la première séance. Pour se faire, il faut :
- ouvrir un terminal
- taper : git clone https://github.com/Bertylle/Projet.git

Un dossier nommé projet se créé normalement dans votre dossier principal. Il contient déjà toutes les données dont j'ai parlé précédemment.

Pour que nous ne trafiquions pas tous les données n'importe comment je nous ai créé chacun une branche où nous pouvons modifier les fichiers et ce personnellement, c'est à dire que dans la branch MASTER se trouvent les fichiers d'origine (il ne faut pas toucher à ceux là). Dans la branch nommée à votre nom vous avez le droit de faire ce que vous voulez !!

Pour aller dans sa branch, il faut taper la commande :
- git checkout mon_nom
puis pour vérifier qu'on est bien sur la bonne branch :
- git branch
