# Procédure pour Git

## Installation de Git (1 fois)

1. Aller sur le site de [Git](https://git-scm.com/)
2. Télécharger la version correspondant à votre système d'exploitation
3. Installer Git en suivant les instructions
4. Configurer Git avec les commandes suivantes:
    - `git config --global user.name "VotreNom"`
    - `git config --global user.email "VotreAdresseMail"`

## Démarrage d'un projet

1. Créer un répertoire pour le projet sur GitHub.
2. Créer un dossier vide sur votre ordinateur et l'ouvrir dans VSCode
3. Initialiser un dépôt Git dans le dossier avec la commande `git init`
4. Ajouter le lien du dépôt GitHub avec la commande `git remote add origin lienDuDepotGitHub`
5. Synchroniser la branche master avec la commande `git pull origin master`

## Suivi des modifications

1. Vérifier l'état des fichiers avec la commande `git status`
2. Synchoniser les fichiers avec le dépôt GitHub avec la commande `git pull origin master`
3. Ajouter les fichiers modifiés avec la commande `git add --all`
4. Valider les modifications avec la commande `git commit -m "Message de validation"`
5. Envoyer les modifications sur GitHub avec la commande `git push -u origin master`
