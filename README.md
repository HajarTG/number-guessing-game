## Number Guessing Game — Bash & PostgreSQL


Un petit jeu de devinette en Bash où l'utilisateur doit deviner un nombre aléatoire entre 1 et 1000. Le script enregistre les performances de chaque joueur dans une base de données PostgreSQL : nombre de parties jouées et meilleur score (moins de tentatives).

### Fonctionnalités :

Création automatique d’un utilisateur si c’est sa première fois
Affichage des statistiques pour les joueurs existants
Validation des entrées (seuls les entiers sont acceptés)
Indices en temps réel : "plus haut" / "plus bas"
Mise à jour en temps réel de games_played et best_game
Gestion des données avec psql et pg_dump

### Technos utilisées : 
Bash, PostgreSQL, Git
### Objectif :
Maîtriser l’interaction entre scripts Bash et bases de données relationnelles
