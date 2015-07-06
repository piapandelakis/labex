# labex
Dossier pour le développement du projet Cinéphilies Sériphilies 2.0

Tâches réalisées le 4 juillet : installé Xcode, créé le dépôt comme tu vois, créé en même temps ce fichier readme, et essayé depuis la console de faire un push du dossier "labex" en local vers le dépôt distant... j'arrive à définir ce dépôt comme origin, mais au moment de balancer les dossiers ça ne marche plus. Je te mets ce que j'ai fait et où je bloque : 

MacBook-Pro-de-Pia:/ piapandelakis$ cd Applications  
MacBook-Pro-de-Pia:Applications piapandelakis$ cd MAMP  
MacBook-Pro-de-Pia:MAMP piapandelakis$ cd htdocs  
MacBook-Pro-de-Pia:htdocs piapandelakis$ cd labex  
MacBook-Pro-de-Pia:labex piapandelakis$ git init  
Reinitialized existing Git repository in /Users/piapandelakis/Dropbox/labex/.git/  
MacBook-Pro-de-Pia:labex piapandelakis$ git add .  
git commit -m 'First commit'  
MacBook-Pro-de-Pia:labex piapandelakis$ git commit -m 'First commit'  
[master (root-commit) 8f75bbf] First commit  
git remote add origin https://github.com/piapandelakis/labex-inprogress.git  
 1277 files changed, 139683 insertions(+)  

(ici liste des fichiers)

MacBook-Pro-de-Pia:labex piapandelakis$ git remote add origin https://github.com/piapandelakis/labex-inprogress.git  
MacBook-Pro-de-Pia:labex piapandelakis$ git push origin master  
Username for 'https://github.com': PiaPandelakis  
Password for 'https://PiaPandelakis@github.com':  
To https://github.com/piapandelakis/labex-inprogress.git  
 ! [rejected]        master -> master (fetch first)  
error: failed to push some refs to 'https://github.com/piapandelakis/labex-inprogress.git'  
hint: Updates were rejected because the remote contains work that you do  
hint: not have locally. This is usually caused by another repository pushing  
hint: to the same ref. You may want to first integrate the remote changes  
hint: (e.g., 'git pull ...') before pushing again.  
hint: See the 'Note about fast-forwards' in 'git push --help' for details.  
MacBook-Pro-de-Pia:labex piapandelakis$

*Tu viens de créer une origine mais je ne suis pas sur que tu ais récupéré le readme de github ???*
*Il te dit donc de faire un git pull pour récupérer d'abord le readme pour pouvoir ensuite pousser sur github*
*Le truc c'est de gérer les conflits sur ta machine et pas sur le dépôt distant, si tu envoies sans avoir récupéré le dépot distant tu vas mettre des conflits sur le dépot distant (on ne veut pas ça)*

##Solution dhébergement##
https://github.com/walutisme/grav-test

On peut synchroniser Dropbox avec un hérbergement Heroku. Heroku permet de faire tourner du PHP. Dropbox de synchroniser les fichiers de contenu.  
On pourrait donc facilement gérer le génération du site.

A tenter
