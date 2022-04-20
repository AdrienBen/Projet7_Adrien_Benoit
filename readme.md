## Backend 

Avoir ouvert un terminal au préalable et être dans le dossier backend (cd backend) en suite mettre les lignes suivantes :

- npm install 
- node server 

---

## Frontend

Ouvrir un nouveau terminal et être dans le dossier frontend (cd frontend) en suite mettre les lignes suivantes :



- npm install
- npm run serve

---

## MySQL 

Penser à vous diriger dans le dossier (/backend/.env), n'oubliez pas de mettre votre mot de passe et votre nom à jour.

- DB_USER=root (mettre le vôtre)
- DB_PASS= (mettre vôtre mot de passe)

Après ouvrir vôtre logiciel MySQL Command Line client et mettre ces quelque ligne de commande :

- Create DATABASE groupomania;
- USE groupomania;

Importer le fichier groupomania.sql :

- source (mettre le chemin vers le fichier groupomania.sql);

Si vous rencontrez des difficultés avec certaines erreur faites cette suite de commande :

 Etapes 1 : -show tables; 

 Etapes 2 : Vous êtes dans le fichier groupomania (en utilisant USE groupomania ) vous allez voir un tableau. 

 Etapes 3 : Vous devriez voir ceci dans le tableau Tables_in_groupomania ( comment, like, post, user ) 

 Etapes 4 : Retourner sur visual studio code ou autre logiciel. Aller Directement dans le fichier groupomania.sql et faites un CTRL + A ensuite retourné sur MySQL et copié le directement clique droit paste)

 Etapes 5 : Vous avez fini et vous devriez voir ( 4 rows in set (0.00 sec)) 

 Etapes 6 : C'est bon vôtre base de donnée est mise

 ---

 Vous avez un compte Admin à votre disposition :

 - admin.admin@admin.com
 - Admin418@