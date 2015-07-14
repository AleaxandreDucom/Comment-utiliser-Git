# hello-world
Une démo d'utilisation de Git avec Github


## Mémento des principales commandes Git
- **git init :** initialisation d'un projet (si le projet est créé depuis github, ne pas utiliser cette commande) ou réinitialisation d'un projet existant
- **git status :** vérifier le statut, l'état (si modification de fichier) du répertoire de travail (le repository)
- **git add nom_du_fichier :** ajoute un nouveau fichier (du répertoire de travail) à l'index
- **git commit -m "Phrase_explication_détaillée_du_commit" :** Ajouter les fichiers de l'index dans un commit
- **git commit -am "Phrase_explication" :** ajouter les fichiers au repositery, directement sans le add si le fichier est déjà ajouté - update de fichiers
- **git log :** Voir l'historique des modifications du commit sous forme de liste
- **git checkout sha_du_commit :** se positionner sur un ancien commit - attention le retour à un commit efface les commits les plus récents - si push après retour
- **git checkout master :** retour au commit principal - le dernier
- **git clone https_ssh_adresse_du_repositery_github :** rapatrier / clôner les sources d'un remote github vers un ordinateur local
- **git push origin master :** envoyer les modifications des fichiers (le commit) vers github (le remote)
- **git pull origin master :** récupérer les modifications effectuées par d'autres développeurs sur un remote
- **git branch nom_de_la_branche :** créer une branche
- **git checkout nom_de_la_branche_créée :** se positionner sur la branche créée
- **git checkout -b nom_de_la_branche :** créer une branche et se positionner sur la branche créée
- **git push --set-upstream origin branche-test-01 :** envoyer la branche créée sur le remote Github
- **git push :** envoyer les commit dans la branche créée sur le remote (possibilité d'ommettre origin et nom_de_la_branche)

## Commandes terminal
- **mkdir :** créer un répertoire
- **cd nom_dossier_créé :** se placer dans le dossier créée
- **cat nom_du_fichier :** lire le contenu d'un fichier par l'intermédiaire d'un terminal

## Actions classiques de base
1. Coder
2. Commit
3. Push

##Lexique
- **Origin :** nom du remote par défaut si remote unique dans un projet
- **Master :** nom de la branche principale d'un repository
- **Une branche :** "un autre chemin" pour tester, expérimenter, modifier le code existant du "chemin principal" (master) ou bien crééer une nouvelle fonction sans toucher au code master