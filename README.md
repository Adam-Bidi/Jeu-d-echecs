# Jeu-d-echecs

Déroulé du projet : 

Nous nous sommes d'abord concentrés sur la création des pièces et du plateau. Pour cela, nous avons utilisé les pièces du jeu chess.com. Pour initialiser le plateau et les pièces, nous avons fait usage de chatgpt afin de comprendre certaines fonctions comme screen.blit ou pg.image.load. 

Nous nous sommes ensuite penchés sur les mouvements des pièces, et notamment renvoyer un booléen pour savoir si le mouvement est valide. Cela a constitué une grande partie de notre travail, car il fallait coder tous les mouvements possibles pour chaque type de pièce.

Ensuite, nous avons géré l'interface utilisateur.

Puis nous nous sommes intéressé au module main.py. La partie la plus difficile a été le débuguage, car pendant longtemps nos pièces ne bougeaient pas, bien qu'elles s'affichaient. Cela provenait de divers problèmes dans le module main.py.

Cependant, à partir du moment où quelques pièces bougeaient (les pions par exemple), beaucoup d'autres bugs sont survenus car Python parcourait effectivement les différentes fonctions de déplacements autorisés. Nous avons essayé de débuguer au maximum, cependant étant donné que nous avons sous-estimé la charge de travail du projet, nous n'avons pas réussi à finir le projet dans les temps. Ainsi, les pions ne mangent pas correctement, la saut de 2 cases pour les pions ne fonctionne que pour les noirs et est valable plusieurs fois, la prise en passant ne mange pas la pièce, le roi et la reine ne bougent pas, et nous n'avons pas codé la mise en échec, le roque et l'autopromotion.
