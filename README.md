# Description

Ce projet a pour bute de créer un petit programme capable de dessiner/supprimer des rectangles sur des images
et de les enregistrer au format .json.

Ce projet à vue le jour en 1 semaine afin de répondre à un problème de donnée incomplète dans un projet d'apprentissage avec du deep learning.

Il a été accompagné de la création d'une mini librairie permettant la lecture de fichier Json à partir du C++.

# Installation
Installer JSONReader :

Clonez : https://github.com/Inagaroth/JSONReader
Puis compilez et mettez la librairie dans le dossier /lib.
Les headers sont déjà inclus dans le dossier correspondant.

Installer la sfml :
```sudo apt-get install libsfml-dev```

Lancer make dans le dossier Rekt :
```make```

Lancer le programme  à partir du dossier REKT avec : ```./bin/REKT```

Les images et fichiers .piff doivent se situer toutes sous le dossier./Ressources/Datas.

# Utilisation

Le programme permet d'ajouter et de supprimer des annotations sur une image.
Les boutons du dock permettent respectivement de passer en modeajouter une annotation,en mode supprimer, passer à la page précédente, passer à la page suivante.

Chacunes de ces fonctions peut être réalisées avec un raccourci :
- Q : image précédente
- D : image suivante
- S : Screenshot (non disponible dans le dock), les images sont sauvegardées sous le dossier ./out
- 1 : passer en mode ajout
- 2 : passer en mode suppression.

# Remerciement

Les icons du dock proviennent du site : https://www.flaticon.com/

Auteurs de ces icones : Lucy G, Freepik et Smashicons.

# Licence

Le code source et le programme qui en résulte sont sous licence GPL.

Les icones eraser.png, left-arrow.png, right-arrow.png et pencil.png sont sous la license inclue dans le dossier.

Le reste des images sont également sous licence GPL.

# Autheur

**Nicolas Cuadros**