L'idée pour ce restaurant était de créer une enseigne gluten-free et bio misant sur une nourriture saine et appétissante.
Le titre évoquant le pain est évidemment un jeu de mot car le pain est la première nourriture que les personnes intolérantes au gluten ne peuvent plus manger.
Le gluten se trouve essentiellement dans la farine de blé ce qui impose aux personnes intolérantes de manger du pain spécial à base de farine de riz, de sarrasin, ...
La même idée s'applique également aux pâtes, aux pizzas, au hamburgers, aux tartes,...
Il est donc tout à fait possible pour une personne intolérante au gluten de manger normalement chez elle mais beaucoup de restaurants ne propose pas encore d'options gluten-free intéressante d'ou l'intérêt de créer un restaurant qui propose des pâtes, pizzas, dessert et pain sans-gluten aux personnes concernées.

Pour celà, je voulais donc intégrer le mot pain dans le titre et utiliser un background qui illustre le propos et aère également la présentation du site.
La majorité du contenu est ensuite intégrée dans une grid bootstrap avec un fond légèrement transparent et d'importantes margins gauche et droite en résolution desktop afin que le pain reste visible en tout temps.
Sur suggestion du coach, j'ai utilisé une fonction js afin de coller le menu au sommet de la page après un scroll vers le bas pour qu'il soit toujours accessible pour l'utilisateur.

Concernant la page restaurants, pour assurer une bonne mis-en-page pour les résolutions xs et md, j'ai réalisé 2 versions différentes du tableau des horaires : une en trois colonnes pour la résolution md et une en deux colonnes pour la résolution xs. Les propriétés d-none et d-block se chargent ensuite d'afficher la bonne version en fonction de la résolution de l'écran.
La photo de restaurant apparaissant au-dessus du menu est également affichée selon ce principe.

Les principales difficultés furent de gérer la taille de l'affichage des images car tant le fichier css que le html en bootstrap pouvaient être utilisés à ces fins.

De même, la gestion de la transparence présenta un léger challenge car il fallait faire en sorte que la transparence n'affecte que la couleur de fond et pas le contenu.
Le problème fut régler en codant la background color en RGBa. 

Enfin, la superposition du logo "Bouchée de pain" sur la banderolle (photo du restaurant) fut la dernière difficulté et fut réglée via une petite révision des propriétés z-index et position (relative et absolute).


Ci-dessous, les données de références pour le contenu du site.
Les adresses sont bien évidemment fictives et évoquent chacunes une céréale utilisées dans les préparations sans gluten.

Restaurants :

- Bouchée de pain
    "Sain et pas cher"

    "Parce qu'il ne faudrait pas choisir entre manger bon et manger bien, <b>Bouchée de pain</b> se donne pour mission d'apporter les bienfaits d'une cuisine saine, appétissante et accessible à toutes les bourses."
    
    carte 1
        Pastafolies 
        Au maïs, au riz, au sarrasin, multi-céréales,...
        le mardi, c'est pastas à volontés pour tous les goûts et à toutes les sauces ! 
    carte 2
        Cuisine saine
        Envie de devenir un chef vous-même ?
        Venez participer à nos cours de cuisine bio et gluten-free.
        Vous avez une allergie peu courante ? Tant mieux ! 
        Chez "Cuisine saine", on aime relever des défis.. tous ensemble !



    Rue du Sarrasin n°30, 1000 Bruxelles
    02/222.22.22
    &
    Rue du petit Epautre n°29, 1410 Waterloo
    02/333.33.33
    
    lundi	    Fermé
    mardi	    18:30–22:00
    mercredi	18:30–22:00
    jeudi	    18:30–22:00
    vendredi	18:30–22:30
    samedi	    11:00–15:00, 18:00–22:30
    dimanche	11:00–15:00, 18:00–22:00

    
        Sharing
        Guacamole & patate douce

        Patate douce- graines torréfiées - avocat - oignons rouges
        7,50€
        
        Quesadilla Jalapeños

        Fromage, coriandre et jalapeños, guacamole, salsa & crème épaisse
        9,50€
        
        Quesadilla poivrons

        Poivrons, fromage, coriandre, guacamole
        9,50€
        
        Nachos Locos for 2 pers

        Nachos gratinés au four guacamole, salsa & sour cream
        10,00€
        
        PLats
        Boeuf confit

        Boeuf basse température - laqué sauce Bbq - graines torréfiées - jus de cuisson
        18,00€
        
        Fish & Dips

        Cabillaud en accras - chutney orange gingembre - sauce verte et frites
        15,00€
        
        Poulet

        Filet de poulet grillé- épices Cajun - crème coco - noix de cajou grillées - frites
        16,50€
        
        Saumon

        Saumon cuit basse température - graines de moutardes - algues - émulsion yuzu - pomme de terre douce
        17,00€
        
        Supplément
        Pain sans gluten
        2,00€
        
        Fromage
        1,50€
        
        Bacon
        1,50€
        
        2 Tacos
        2,50€
        
        Haché burger de boeuf
        4,00€
        
        Frites, patates douces ou salade
        4,00€
        
        Burgers
        Super Moine

        Bun fait maison - Boeuf - confit d’oignons - bacon grillé - vieux gouda - oignon grillés - moutarde - roquette - frites
        16,50€
        
        Cheese

        Bun fait maison - Boeuf - salade - mayonnaise - tomate - cornichon - oignons rouges - vieux gouda - frites
        16,00€
        
        Gringo

        Bun fait maison - Haché de boeuf - salsa maison, iceberg - jalapeños - guacamole, vieux gouda, mayonnaise - oignons rouges - frites
        17,00€
        
        Popeye

        Bun fait maison - Burger d’épinards - confit d’oignons - salade - fromage frais - courgette - pommes de terre douces
        17,00€
        
        Nordic

        Bun fait à l’encre de sèche - Saumon basse température, betterave - roquette - sauce wasabi câpres - fromage frais, frites
        17,00€
        
        Kids
        10,00€
        Blanc de poulet grillé frites
        Ou fish & dips frites
        Ou Viande Hachée boeuf
        1,00€ +
        
        Ou Hamburger kids
        2,00€ +
        
        Glace
        Tacos & salades
        Tacos ceviche

        Saumon ceviche - salade de tomate - crème épaisse - guacamole - houmous - sauce verte citronnée - aubergine & courgette grillées - Tortillas
        16,00€
        
        Tacos Végé

        Aubergine - courgette - salade de tomate - patate douces grillées - crème épaisse - guacamole - houmous - sauce verte citronnée - Tortillas
        16,00€
        
        Tacos Boeuf

        Boeuf - salade de tomate - Aubergine et courgette grillées - crème épaisse - guacamole - houmous - sauce verte citronnée - Tortillas
        16,00€
        
        Salad L’amour Fou

        Quinoa - Salade mixte - patate douce - courgette grillée - amandes torréfiées - herbes fraîches
        13,00€
        
        Option pour salade l’amour Fou
        Saumon rôti
        3,00€ +
        
        Portobello fromage de chèvre
        3,00€ +
        
        Mozzarella di buffala
        3,00€ + 
