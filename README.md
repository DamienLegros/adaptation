# adaptation-project

Nous avons sélectionnée l’énigme suivante, étant celle qui offre le plus de possibilités d’adaptation parmi
les 4 énigmes décrites dans le cahier des charges. 

L’environnement de l’énigme comprend les éléments suivants :
- Un pistolet que le joueur peut prendre et avec lequel il peut tirer.
- Un personnage non jouable (PNJ) à qui le joueur pourra s’adresser ou tirer dessus.
- Un boîtier contenant un interrupteur pour obtenir la clé pour ouvrir la porte.
- Une cible sur laquelle le joueur pourra tirer.

Le joueur aura 4 manières différentes d’ouvrir la porte :
1. Discuter avec le PNJ et répondre à son énigme à choix multiples pour ouvrir la porte. (ACTION SOCIALIZER)
2. Tirer sur le PNJ avec le pistolet. Une fois fait, le PNJ lâchera une clé pour ouvrir la porte. (ACTION KILLER)
3. Tirer sur la cible avec le pistolet, le score du joueur augmentera à chaque cible touchée jusqu’à donner la clé pour ouvrir la porte. (ACTION ACHIEVER)
4. Trouver et ouvrir le boîtier, enclencher le bouton du boîtier puis ouvrir la porte avec la clé obtenu. (ACTION EXPLORER)

Les positions des objets dans la salle seront placés de manière aléatoire pour avoir une expérience
différente à chaque fois. N’ayant plus qu’une énigme les salles se suivront avec les 4 mêmes actions possibles.
Le niveau de difficulté de chaque action est choisi par rapport aux actions prises précédemment par le joueur
(On augmentera la difficulté d’une action qui est souvent effectuée).
Une adaptation rigide entre les salles de la difficulté sera donc implémenté en plus d’une adaptation
dynamique au sein de chaque salle.
