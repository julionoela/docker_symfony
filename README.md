# docker_symfony
Docker using (php8.3-fpm, nginx and mysql 8)

Requirements :
--------------
- install docker (DockerDesktop for windows)
- Make sure that this ready correctly

Launchment :
------------
- Déplacer dans le repertoire du repository
- lancer la commande "docker compose up --build"
- Ouvrir la navigateur et saisir l'URL "localhost:80" (ports du serveur nginx configurés dans le fichier "docker-compose.yml")

Remarque :
----------
- Si vous voulez lancer une autre projet, juste remplacer les sources dans le dossier "app".
