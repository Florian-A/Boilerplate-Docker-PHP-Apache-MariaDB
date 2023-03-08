# Docker + PHP + Apache + MariaDB
Code commun de départ (boilerplate) fournissant un service Apache + PHP et MariaDB.

## Prérequis :

- docker
- docker-compose
- bash

## Utilisation :

`./start.bash` pour démarrer l´ensemble.

`./stop.bash` pour arrêter l´ensemble.

## Informations :

### Service web :
- PHP 7.3 + Apache 2.

### Service de base de données :
- MariaDB : 10.2
- Hôte : `db`
- Utilisateur : `root`
- Mot de passe : `1234`
- Port : `3306`
