## Installation
* Ouvrir un terminal dans le dossier ou le projet doit être récupéré
* Étape 1 : `$ git clone git@github.com:Yoann-Vie/app-1-wordpress.git`
* Étape 2 : `$ cd app-1-wordpress/docker`
* Étape 3 : `$ docker-compose up -d`

### Accès aux outils de l'application
Ouvrir un navigateur et utiliser les urls suivantes

* Application Wordpress : `localhost`
* Phpmyadmin : `localhost:8080`
* Mailhog : `localhost:8025`

### Utilisation des outils
* Utiliser phpmyadmin pour intéragir avec la base de donnée via une interface graphique
    - Compte mariadb utilisé par l'application
    - Login user : `admin`
    - Mot de passe user : `admin123`
* Utiliser mailhog pour récupérer tous les mails envoyés par l'application, peu importe le destinataire