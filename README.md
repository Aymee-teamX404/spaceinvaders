# spaceinvaders

But : faire un super vaisseau pouvant tuer des monstres avec 3 vies. 
Comment ? grâce à screen et VT100. 
Avec le lien : https://espterm.github.io/docs/VT100%20escape%20codes.html nécessaire à la programmation. 

Ce qu'on sait : 

On va devoir rentrer en intéraction avec screen, ouvrant une fenêtre de taille qu'on aura déjà demandé en amont. Delà on devra avoir plusieurs programmes en intéractions : vaisseau+monstre ; missiles ; score ; petit bouclier. 

On aura donc a gerer une interface avec un missile qui bouge suivant la demande de l'utilisateur. Par choix avec ASCII on va choisir : 

- la touche q pour aller à gauche
- la touche d pour aller à droite
- la barre espace pour tirer 
ATTENTION: si l'utilisateur appuie sur q alors qu'il est au max de l'interface, l'objet n'avance plus vers la gauche. 

Les monstres peuvent se déplacer et tirer en même temps. Pour simplifier on dira qu'un monstre tire toutes les 4 secondes si il est sur la ligne la plus proche du vaisseau. 

Le vaisseau, contrôlé par l'utilisateur n'évolue pas en y, seulement en x. Peut tirer autant de fois qu'il veut. 

Les monstres avancent toutes les secondes. Un à un. 
