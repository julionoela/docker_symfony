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

Acces dans le conteneur php
---------------------------
- Dans la ligne de comande saisir la commande : "docker exec -it <id-conteneur-php> bash"
avec id-conteneur-php est obtenu à parir de la commande 'docker ps'

 Acces dans le conteneur nginx
------------------------------
docker exec -it <id-conteneur-nginx> bash

Access dans le conteneur mysql
------------------------------
docker exec -it <id-conteneur-mysql> mysql -u root -p
