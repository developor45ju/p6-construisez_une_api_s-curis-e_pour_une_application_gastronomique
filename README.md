# PIQUANTE
Cette application web a pour but de vendre nos sauces piquantes à travers une interface web

## Fonctionnalités
**Système d'authentification**
* Login
* Signup

**Gestion des sauces piquantes**
* Création d'une sauce piquante
* Modification d'une sauce piquante
* Suppression d'une sauces piquantes

## Fonctionnement 
1. Inscrivez-vous
2. Connectez-vous
3. Cliquez sur l'encard **ADD SAUCE**
4. Remplisez le nom de la sauce (**OBLIGATOIRE**)
5. Remplisez le fabricant de la sauce (**OBLIGATOIRE**)
6. Remplisez la description de la sauce (**OBLIGATOIRE**)
7. Remplisez le nom du fabricant de la sauce (**OBLIGATOIRE**)
8. Remplisez l'image de la sauce (**OBLIGATOIRE**)
9. Remplisez la force de la sauce (**OBLIGATOIRE**)

## Installation
1. Cloner le dépot, installer les dépendances et lancer le serveur :
```shell
git clone git@github.com:developor45ju/p6-api-rest-app-gastronomique.git
npm install
npm start
```
2. Se rendre sur le [Front-End](https://piquante-j7q6.onrender.com)

## Sécurités

- Argon2, un *algorithme de hashage* pour mot de passe
- dotenv, un package qui permet de créer des variables d'anvironnements pour sécurisé les donnés sensible
- mongoose-unique-validator, pour que l'entrée *email* soit unique dans la base de donnée