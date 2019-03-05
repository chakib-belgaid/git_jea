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
    le ficheir .gitignore 