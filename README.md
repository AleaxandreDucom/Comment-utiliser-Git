# hello-world
Une démo d'utilisation de Git avec Github


## Mémento des principales commandes Git
git init        : initialisation d'un projet (si le projet est créé depuis github, ne pas utiliser cette commande) ou réinitialisation d'un projet existant
git status : vérifier le statut (si modification de fichier) dans le répertoire de travail)
git add nom_du_fichier      : ajoute un nouveau fichier (du répertoire de travail) à l'index
git commit -m "Phrase_explication_détaillée_du_commit" : Ajouter les fichiers de l'index dans un commit
git commit -am "Phrase_explication" : ajouter les fichiers au repositery, sans le add si fichier est déjà ajouté - update de fichiers
git log : Voir l'historique des modifications du commit sous forme de liste
git checkout sha_du_commit : se positionner sur un ancien commit - attention le retour à un commit efface les commits les plus récents - si commit après retour
git checkout master : retour au commit principal - le dernier
git clone : https_ssh_adresse_du_repositery_github : raptrier / clôner les sources d'un remote github vers un ordinateur local
git push origin master : envoyer les modifications des fichiers (le commit) vers github (le remote)
git pull origin master : récupérer les modifications effectuées par d'autres développeurs sur un remote




cat nom_du_fichier : lire le contenu d'un fichier par l'intermédiaire d'unb terminal

##Lexique
Origin : nom du remote par défaut si remote unique dnas un projet
Master : nom de la branche principale d'un repote