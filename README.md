# Mon Premier Projet Node.js

##  Description

Ce projet est une application Node.js complÃ¨te permettant : - De crÃ©er
un serveur HTTP simple - De manipuler des fichiers avec le module `fs` -
De crÃ©er une API REST - D'utiliser Express.js - De gÃ©rer les variables
d'environnement - D'ajouter une interface web simple

------------------------------------------------------------------------

##  PrÃ©requis

-   Node.js installÃ© (https://nodejs.org)
-   npm installÃ©
-   Un Ã©diteur de code (IntelliJ IDEA recommandÃ©)

------------------------------------------------------------------------

## Structure du projet

    mon-premier-projet-nodejs
    â”‚
    â”œâ”€â”€ app.js
    â”œâ”€â”€ server.js
    â”œâ”€â”€ users.json
    â”œâ”€â”€ data.txt
    â”œâ”€â”€ package.json
    â”œâ”€â”€ .env
    â”œâ”€â”€ public/
    â”‚   â””â”€â”€ index.html
    â””â”€â”€ README.md

------------------------------------------------------------------------

##  Installation

### 1ï Cloner ou crÃ©er le projet

``` bash
mkdir mon-premier-projet-nodejs
cd mon-premier-projet-nodejs
npm init -y
```

###  Installer les dependances

``` bash
npm install express morgan dotenv
```

------------------------------------------------------------------------

## Lancer le projet

### l'application Express :

``` bash
node app.js
```

Ouvrir dans le navigateur :

    http://localhost:3000

------------------------------------------------------------------------

## Routes disponibles

### Interface Web

    GET /

### API Utilisateurs

    GET    /api/users        â†’ Liste des utilisateurs
    GET    /api/users/:id    â†’ Utilisateur par ID
    POST   /api/users        â†’ Ajouter un utilisateur

### Exemple JSON pour POST :

``` json
{
  "nom": "Ali",
  "prenom": "Karim",
  "age": 22
}
```

------------------------------------------------------------------------

##  Variables d'environnement

Fichier `.env` :

    PORT=3000
    NODE_ENV=development

------------------------------------------------------------------------

## Modules utilisÃ©s

### Modules natifs :

-   http
-   fs
-   path
-   url

### Modules externes :

-   express
-   morgan
-   dotenv

------------------------------------------------------------------------

## FonctionnalitÃ©s

âœ” Serveur HTTP\
âœ” API REST\
âœ” Lecture et Ã©criture de fichiers\
âœ” Middleware de logs\
âœ” Variables d'environnement\
âœ” Interface utilisateur\
âœ” Gestion des erreurs


<img width="1366" height="728" alt="localhost_3000 - Google Chrome 08_01_2026 13_42_36" src="https://github.com/user-attachments/assets/ea5b641f-2c1b-4088-b039-f0cda8065169" />

<img width="1366" height="728" alt="localhost_3000 - Google Chrome 08_01_2026 13_47_26" src="https://github.com/user-attachments/assets/4ae5fc25-319b-48c8-a8d2-c89a06be6213" />
<img width="1366" height="728" alt="localhost_3000 - Google Chrome 08_01_2026 13_45_12" src="https://github.com/user-attachments/assets/2b5c0c6f-2976-4f34-85bd-f6514d28c703" />
<img width="1366" height="728" alt="localhost_3000 - Google Chrome 08_01_2026 13_47_45" src="https://github.com/user-attachments/assets/35b2b2e7-cf58-430c-8d37-12e1425b5e42" />
<img width="1366" height="728" alt="localhost_3000 - Google Chrome 08_01_2026 13_47_36"<img width="1366" height="728" alt="API Node js - Google Chrome 08_01_2026 13_52_14" src="https://github.com/user-attachments/assets/e047ac3d-0ebf-42d9-9ebb-32884e2edf8c" />
 src="https://github.com/user-attachments/assets/182258f0-cb12-4f73-be82-eb37408b5881" />
