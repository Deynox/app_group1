Th�me : Les s�ries



Base de donn�es
______________________

Acteur : Info sur les acteurs
droit : droit des utilisateurs
genre : Genre des films
realisateur : Info sur les r�alisateurs
series : les series avec leurs infos
series_has_acteur : table de liaison
series_has_genre : table de liaison
series_has_realisateur : table de liaison
util : Info sur les utilisateurs
util_comm_series : le(s) commentaires d'un utilisateurs sur une s�ries bien pr�cises.
until_like_series : Si un utilisateurs aimes ou n'aime pas une s�rieux.[non obligatoires] Le champs avis est �gales a 1 ou 2. 1 pour aime et 2 pour n'aime pas.



Info
______________________

model.html sert juste a avoir un design simpliste sur le quel on peut travailler.
vues/style.css est a concerver / modifier pour adapter le design au besoin.




Objectif :
______________________

Menu :

Un bouton pour revenir a l'accueil
Un bouton "Acteur","R�alisateur" et "Genre"
Un formulaire Login / Pass pour se connecter.



Accueil :

Afficher sur le block de gauche les derniers s�ries ajouter.
Sur le block de droite afficher 3/4 s�ries random.
titre du film, bref description
le(s) r�alisateur (4 max), les acteurs (4 max) cliquable qui am�ne sur leurs descriptions.
les genres(4 Max) qui am�nes sur la page genre avec le bon filtre.



Acteur :

Liste d�roulante avec les acteurs, quand on choisis un acteur on affiche toutes les s�ries dans les quels il a jouer.




R�alisateur / Genre : Idem qu'acteur.



D�tails :

Pour une s�ries on affiche toute la description de la s�ries, ainsi que tous les acteurs, r�alisateurs et genre.
Pour un acteur on affiche ces informations (nom,bio) et une photo. Ainsi que les s�ries dans les quelles il a jouer.
Pour un r�alisateurs on affiche ces informations (nom,bio) et une photo. Ainsi que toutes les s�ries qu'il a produit.



Administration :

On peut ajouter/modifier/supprimer des s�ries,acteurs,r�alisateur et genre.



T�ches :
______________________

