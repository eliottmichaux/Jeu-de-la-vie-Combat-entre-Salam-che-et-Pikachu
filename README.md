Jeu de la vie combat entre Salameche et Pikachu

Les participants de ce projet du 3ème trimestre portant sur le développement d'un jeu de la vie sont : Eliott Michaux, Arthur Savournin, Martin Bravais.

Pour ce projet, nous avons tout d'abord recrée deux pixel art, celui de Pikachu et de Salamèche. Pour réaliser ces derniers, nous avons recrée case par case le pixel art, en respectant la taille ainsi que la couleur originale ! Ensuite, nous avons codé notre propre version du jeu de la vie qui nous permet de simuler un combat entre ces deux célèbres petites bêtes issues du jeu Pokemon. Pour simuler une attaque du Salamèche sur Pikachu, nous avons utilisé un glisseur, censé représenter la célèbre attaque Flammèche de Salamèche. Suite à cette attaque surpuissante, le Pikachu est vaincu et explose, lançant ainsi le jeu de la vie... Comme quoi, la mort peut au final être le début d'une autre vie ! Le fond, le décor change à chaque fois que l'on lance le programme, métaphore de la vie qui se déroule dans des endroits différents à chaque fois qu'elle est crée.

Description des fonctions : 
- make_pikachu = Crée le pixel art de pikachu
- make_salameche = Crée le pixel art de Salamèche
- make_glisseur = Crée le glisseur qui va de Salamèche vers Pikachu
- apply_game_of_life_rules = Création d'une grille optimisée afin de permettre le fonctionnement du code (La partie gauche de la grille ne fait pas le jeu de la vie, permettant au salamèche de ne pas disparaitre lorsque le jeu de la vie commence)
- apply_rules = Création des règles du jeu de la vie qui se déclenche une fois que le Pikachu est touché par le glisseur (simulation d'une attaque de Salamèche)
- modification des couleurs dans data afin d'avoir les couleurs exactes ainsi qu'un fond d'une couleur aléatoire à chaque fois.


Que le combat commence !
