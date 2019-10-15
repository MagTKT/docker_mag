Vous et votre cerveau souhaitez automatiser la création et la configuration d'un environnement de développement autonome que chaque développeur peut utiliser sur sa machine. L'objectif est que tous les développeurs puissent travailler sur un environnement totalement identique.
Pour cela, vous avez décidé d'utiliser Docker. 

Vous devez fournir une solution technique avec Docker permettant à tous les développeurs d'installer rapidement votre application. Celle-ci doit tourner avec :
- Apache / PHP 7.2 avec l'extension pdo_mysql (avec une commande créée par docker, renseignez vous dans la documentation)(un seul container)
- Mariadb
- Mailhog (avec configuration php smtp pour l'utiliser)

En plus de cela, vous devez installer un phpmyadmin/phpmyadmin.

Vous devez utiliser les Dockerfiles et Docker-Compose pour qu'il soit possible en une commande de créer l'environnement pour lancer l'application.
'Php info'
Pour le projet, vous devez créer un fichier index.php dans un répertoire sur lequel vous ferez un volume.
