# Git Initiation  
this is a presentation that aims to introduce git to anyone who isn't familiarized with version managements and has low skills in computer programming. 

- **Duration**:1h:30mn 
- **target**: high-schools teachers 


# Commands 
pour la configuration 

    git config --global user.name "[name]"
    git config --global user.email "[email]"
    git config --global user.passowrd "[pwd]"

Initialisation d'un repo 

    git init 

ajouter des fichiers 

    git add fichier 

faire un commit 

    git commit -m "message" 

verifier le status 

    git status 

comparer la version actuelle avec le dernier commit 

    git diff 

supprimer un fichier 

    git rm 

annuler les changements 

    git checkout -- fichier 

restaurer un ficher 

    git log -- fichier 
    git checkout commithash -- fichier 

ignorer les fichiers: 
    le fichier .gitignore 

ajouter une branche 

    git branch b 

basculer vers une branche 

    git checkout b

comparer entre deux branches 

    git diff b1..b2 

    git branch --merged 


supprimer une branche 

    git branch -d b2 

enregistrer un travail incomplet 

    git stash 

telecharger une copie 

    git clone addr

recuperer les changements depuis le serveur 

    git fetch origin


merger avec le serveur 

    git merge origin/master 

mise ajour dans le server 

    git push origin master 

sauvegarder les identifiants 

     git config credential.helper store

afficher le graph 

alias graph="git log --all --decorate --oneline --graph" 