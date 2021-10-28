# ProjetYnovB2
Le sujet des projets de groupe
Un projet au choix parmi deux, à réaliser en groupe de 2-3 étudiants, et à rendre pour le 1 décembre. Ils couvriront ce qui a été vu et pratiqué du cours 1 à 7.

Notation : un projet fonctionnel et respectant les différents points demandés donnera au moins la moyenne.
Le respect des spécificités du langage, des bonnes pratiques vues en cours, des normes de nommage donneront des points en plus.
Un versioning via git est obligatoire, ainsi qu’un post sur Github. Tout code livré sans historique sera soupçonné de plagiat.
Chaque projet sera accompagné d'un document explicatif résumant le travail de chaque membre du groupe, et un rapide descriptif de la méthodologie. Un Readme fera l’affaire.

Sujet 1 : un jeu de dame en mode console.
Règles standards (https://fr.wikipedia.org/wiki/Dames).
Le jeu pourra être à un joueur (contre une IA qui sera des mouvements aléatoires-respectants les règles!) ou deux joueurs.
Particularités : un nouveau fichier .txt sera généré à chaque partie, enregistrant tous les mouvements(case départ et case arrivée), ainsi que l'état final du plateau.
La façon dont les mouvements sont demandés au joueur est libre.
Chaque joueur aura un pseudo(demandé en début de partie). Un fichier (format libre) de résultats reprenant les pseudo sera mis à jour à chaque partie avec les nombres de victoires et de défaites.
Tout ce qui n'est pas imposé dans les instructions est libre.



Sujet 2 : simulateur de vol spatial, en mode console.
L'objectif de l'application est de transporter tous les individus présent sur Terre vers d’autres planètes via des vaisseaux en un minimum de temps et de ressources.
Nous nous baserons sur les planètes du système solaire.

Toutes les informations des planètes sont dans un fichier fourni (Planetes.properties), que l'application devra lire. Chaque planète aura un nom, une population de départ, une certaine capacité d’accueil et une distance par rapport à la Terre exprimé en unité (exemple distance entre Terre-Mars : 6 UA-unité astronomique).


Chaque vaisseau aura une capacité de transport, une consommation de carburant par UA (exemple une fusée pourra transporter 4 voyageurs, et consomme 2 unité carburant par unité astronomique) et un coût de création en UC. Les informations sur les vaisseaux sont dans le fichier Vaisseaux.properties.
Chaque opération (création, embarquement, débarquement) liée aux vaisseaux coûtera 1 UC.

Il faudra créer un menu pour créer des vaisseaux, charger les vaisseaux en voyageur, les envoyer et les décharger.
Un compteur devra indiquer à chaque opération le nombre d'UC dépensés.

Chaque opération devra être enregistrée dans un fichier de texte.

Lorsque la Terre n'aura plus aucun habitant et que ceux ci seront sur les autres mondes, l'application affiche les résultats (nombre d'UC dépensées, nombre de tours écoulés).

Les principes de POO devront être appliqués.

Tout ce qui n'est pas imposé dans les instructions est libre.

Bon courage!

N'hésitez pas si vous avez des questions : marc.deschamps@ynov.com
