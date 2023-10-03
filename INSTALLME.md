# Installation du projet 

## 1 .Installer les dépendances 
### Pour initialiser le projet, il faut lancer dans un terminal à la racine du projet la commande suivante : 
`composer install`

### Cette commande récupère et installe toutes les dépendances qui sont nécessaires au projet.

## 2 . Configurer la base de données

### Via le fichier `.env` , remplir la variable globale `DATABASE_URL` pour se connecter à la base de données, puis lancer la commande `php bin/console doctrine:database:create` afin de créer la BDD grâce à cette variable.
