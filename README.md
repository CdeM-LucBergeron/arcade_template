# Premier TP sur Arcade!
Modifier le code du modèle de base afin d’y ajouter les fonctionnalités suivantes :

- Écrire une classe balle
	- Elle contient les attributs suivants:
		- x, y <- La position de la balle
		- change_x, change_y <- représente la vitesse de déplacement de la balle
		- size <- la grosseur (entre 10 et 30)
		- color <- la couleur de la balle (tuple)
	- Avoir une méthode statique qui permet de créer une balle
	- Avoir une méthode qui permet de faire une mise à jour de la position (update).
		- il faut valider que la balle ne sorte pas de l'écran
	- Avoir une méthode draw pour dessiner la balle à l’écran

- Écrire une classe Rectangle qui contient:
	- les attributs suivants:
		- x, y <- la position du rectangle
		- change_x, change_y <- la vitesse de déplacement
		- width, height <- largeur et hauteur
		- color <- la couleur (tuple)
		- angle <- l'angle du rectangle (float)
	- Avoir une méthode statique qui permet de créer un Rectangle
	- Avoir une méthode qui permet de faire une mise à jour de la position (update).
		- il faut valider que le Rectangle ne sorte pas de l'écran
	- Avoir une méthode draw pour dessiner la balle à l’écran


- La classe MyGame doit avoir:
	-  Les attributs suivants:
		- une liste pour contenir les balles
		- une liste pour les rectangles
	- À chaque clique du bouton de gauche de la souris
		- ajouter une balle à l'endroit du clic
	- À chaque clique du bouton de droite de la souris
		- ajouter un rectangle à l'endroit du clic
