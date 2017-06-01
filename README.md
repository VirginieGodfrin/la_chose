
# Commandes git

> Espace de travail => stage => head

## Les basiques
* _git init_ : création du git  
* _git clone https://github.com/..._ : cloner un projet distant  
* _git status_ : montre les fichiers modifiés  
* _git add ._ : ajoute tous les fichiers au stage  
* _git commit -m"..."_ : crée un commit avec un commentaire  
* _git log --summary_ : montre les différents commits exécutés  

* _git remote add origin https://github.com/..._: Création du repo sur un serveur distant  
* _git push_ : envoie au serveur distant  

* _git pull_ : mets à jour le fichier local suite à des modifs sur le serveur distant  
* _git diff HEAD_ : montre les différences dans le head  
* _git diff __staged : montre les différences dans le stage

## Les branches  
* _git branch fin_: creation de la branche fin
* _git push origin fin_: creation de la branche fin sur le serveur distant  
* _git checkout fin_: on se positionne sur la branche fin  
* _git checkout master_: on se positionne sur la branche master  
* _git branch_: montre sur quelle branche on travaille  

* __Mettre à jour la branche master après modif sur la branche fin__  
1_ Toujours sur la branche fin, commitez les dernières modifs sur la branche fin : _git commit -m"last change"_  
2_ Se positionner sur la branche master : _git checkout master_  
3_ Fusionner la branche fin dans la branche master : _git merge fin_  
4_ Supression d'une branche : _git branch -d clean-up_  

## Sources et liens 
[Git guide](http://rogerdudler.github.io/git-guide/index.fr.html)//[Try github](https://try.github.io/levels/1/challenges/1)//
[Learn Git Branching](http://learngitbranching.js.org/)  