# Answers of Elias Pellaud EliasPellaud233

## Basics

### Task 1:

 On trouve les fichiers copiés de git et un fichier .git qui est le fichier qui relie le fichier local et git. 

### Task 2:

 Dans git status, une nouvelle ligne est apparu car nous avons créé un nouveau fichier le README.md. Il a affiché les deux modifications récentes: le README.md et les modification de ce document.  le git log --oneline n'a pas changé

### Task 3:

  le README.md était en untracked files et il est passé en new file ce qui montre que l'on a bien ajouter le fichier

### Task 4:

 Il détecte que l'on a modifier le README.md.

### Task 5:

-C'est le code short hash qui permet d'identifier le commit

-Le HEAD->main signifie que l'on commit nos fichier locaux dans le main 

-"ADD: README file" qui est le message que l'on a spécifié au moment de commit.

### Task 6:

 Nous avons spécifier le commit initial ce qui nous a fait revenir à la première version ou le answers.md était "vierge" et que README.md n'était pas encore crée. Au moment de revenir sur le main, la version du fichier est revenu avec les modifications apporté( answers.md modifié et README.md créé et modifié)

( j'ai oublié de commit à ce moment la je l'ai fais par la suite)

## Gitgraph

### Task 7

1=Nom de la branche 

2=L'identifiant du commit

3=message du commit

4=le nom de la personne qui a fait le commit

5=La version du main

6=La branche develop

7=Une nouvelle branche feature-auth qui part du main et qui est push sur develop

8=La branche main

9=La branche develop

10= le commit initial du projet

![Gitgraph](img/gitgraph.svg)