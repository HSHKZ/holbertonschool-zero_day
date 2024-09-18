# holbertonschool-zero_day

(ENG) : Welcome to the `holbertonschool-zero_day` repository! This project will introduce you to essential concepts of source code management, Git, and GitHub, while helping you gain proficiency with the command line.

(FRA) : Bienvenue dans le référentiel `holbertonschool-zero_day` ! Ce projet vous présentera les concepts essentiels de la gestion du code source, de Git et de GitHub, tout en vous aidant à maîtriser la ligne de commande.

## Table of Contents / Table des matières

- [Introduction](#introduction) / - [Introduction](#introduction)
- [Concepts](#concepts) / - [Concepts](#concepts)
- [Resources](#resources) / - [Ressources](#ressources)
- [Learning Objectives](#learning objectives) / - [Objectifs d'apprentissage](#objectifs d'apprentissage)
- [Requirements](#requirements) / - [Exigences](#exigences)
- [Files](#files) / - [Fichiers](#fichiers)
- [Installation](#installation) / - [Installation](#installation)
- [Basic Git Usage](#basic git usage) / - [Utilisation de base de Git](#utilisation de base de git)
- [Advanced Git Features](#advanced git features) / - [Fonctionnalités avancées de Git](#fonctionnalités avancées de Git)
- [Collaboration on Git](#collaboration on git) / - [Collaboration sur Git](#collaboration sur git)
- [Good Practices](#good practices) / - [Bonnes Pratiques](#bonnes pratiques)
- [Conclusion](#conclusion) / - [Conclusion](#conclusion)

## Introduction

(ENG) : This repository is part of the holbertonschool curriculum and is designed to help you understand the basics of version control with Git and GitHub. By the end of this project, you will be able to explain key concepts, work with Git from the command line, and collaborate on projects efficiently.

(FRA) : Ce référentiel fait partie du programme Holbertonschool et est conçu pour vous aider à comprendre les bases du contrôle de version avec Git et GitHub. À la fin de ce projet, vous serez en mesure d'expliquer les concepts clés, de travailler avec Git depuis la ligne de commande et de collaborer efficacement sur des projets.

## Concepts

(ENG) : For this project, the following key concepts will be explored:

(FRA) : Pour ce projet, les concepts clés suivants seront explorés:

- (ENG) : `Source Code Management (SCM)`: The process of tracking and managing changes to software code.
- (FRA) : `Gestion du code source (GCS)`: Processus de suivi et de gestion des modifications apportées au code logiciel.

- (ENG) : `Git`: A distributed version control system that helps developers track code changes and collaborate on projects.
- (FRA) : `Git`: Un système de contrôle de version distribué qui aide les développeurs à suivre les modifications de code et à collaborer sur des projets.

- (ENG) : `GitHub`: A platform built on top of Git, used for hosting code, collaborating on repositories, and managing projects.
- (FRA) : `GitHub`: Une plate-forme construite sur Git, utilisée pour héberger du code, collaborer sur des référentiels et gérer des projets.

- (ENG) : `Branches`: Used to work on different versions of a project in parallel.
- (FRA) : `Branches`: Permet de travailler en parallèle sur différentes versions d'un projet.

- (ENG) : `Commits`: Snapshots of the repository's state at a particular time, containing changes made to the code.
- (FRA) : `Commits`: Instantanés de l'état du référentiel à un moment donné, contenant les modifications apportées au code.

## Resources / Ressources

(ENG) : Before starting, you should review the following resources:

(FRA) : Avant de commencer, vous devez consulter les ressources suivantes:

- (ENG) : Git : Resources to learn Git
- (FRA) : Git : Ressources pour apprendre Git
- (ENG) : About READMEs
- (FRA) : À propos des README
- (ENG) : How to write a Git commit message
- (FRA) : Comment écrire un message de commit Git

### For advanced users / Pour les utilisateurs avancés:

- (ENG) : Learning branching
- (FRA) : Apprendre le branchage

- (ENG) : Effective pull requests
- (FRA) : Demandes de tirage efficaces

## Learning Objectives / Objectifs d'apprentissage

(ENG) : By the end of this project, you will be able to:

(FRA) : À la fin de ce projet, vous serez capable de:

- (ENG) : Explain source code management and why it's important.
- (FRA) : Expliquez la gestion du code source et pourquoi c'est important.

- (ENG) : Define what Git and GitHub are and their differences.
- (FRA) : Définir ce que sont Git et GitHub et leurs différences.

- (ENG) : Create and manage a repository.
- (FRA) : Créer et gérer un référentiel.

- (ENG) : Write a README.md file for your project.
- (FRA) : Écrire un fichier README.md pour votre projet.

- (ENG) : Commit changes and write meaningful commit messages.
- (FRA) : Validez les modifications et rédigez des messages de validation significatifs.

- (ENG) : Push and pull code to/from GitHub.
- (FRA) : Poussez et extrayez du code vers/depuis GitHub.

- (ENG) : Create and work with branches.
- (FRA) : Créer et travailler avec des branches.

- (ENG) : Merge branches and resolve conflicts.
- (FRA) : Fusionner les branches et résoudre les conflits.

- (ENG) : Collaborate on a project with multiple contributors.
- (FRA) : Collaborer sur un projet avec plusieurs contributeurs.

- (ENG) : Understand which files should or should not appear in a repository.
- (FRA) : Comprendre quels fichiers doivent ou ne doivent pas apparaître dans un référentiel.

## Requirements / Exigences

### General

- (ENG) : All commands should be executed via the command line.
- (FRA) : Toutes les commandes doivent être exécutées via la ligne de commande.

- (ENG) : No GitHub web UI should be used, except for actions that can't be performed from the command line.
- (FRA) : Aucune interface utilisateur Web GitHub ne doit être utilisée, à l'exception des actions qui ne peuvent pas être effectuées à partir de la ligne de commande.
    
- (ENG) : You must provide
- (FRA) : Vous devez fournir:

1. (ENG) : A README.md file at the root of the repository, describing the repository.
1. (FRA) : Un fichier README.md à la racine du référentiel, décrivant le référentiel.

2. (ENG) : A README.md file in the git/ folder, describing the purpose of this sub-project.
2. (FRA) : Un fichier README.md dans le dossier git/, décrivant le but de ce sous-projet.

- (ENG) : Tools Needed: 
- (FRA) : Outils nécessaires:

1. (ENG) : Git: You should have Git installed on your system. Use the following command to install it on Ubuntu:
1. (FRA) : Git : Git devrait être installé sur votre système. Utilisez la commande suivante pour l'installer sur Ubuntu:

- sudo apt-get update
- sudo apt-get upgrade
- sudo apt-get install git

- (ENG) : Text Editor: You can use vim, nano, or any other text editor of your choice to write and edit files.
- (FRA) : Éditeur de texte : vous pouvez utiliser vim, nano ou tout autre éditeur de texte de votre choix pour écrire et éditer des fichiers.

## Installation

(ENG) : To get started with this project, clone the repository to your local machine:

(FRA) : Pour démarrer ce projet, clonez le référentiel sur votre ordinateur local:

```bash
git clone https://github.com/username/holbertonschool-zero_day.git

Once cloned, navigate to the project directory / Une fois cloné, accédez au répertoire du projet:

cd holbertonschool-zero_day
```

## Basic Git Usage / Utilisation de base de Git

(ENG) : The following are the basic commands you'll use to interact with Git:

(FRA) : Voici les commandes de base que vous utiliserez pour interagir avec Git:

1. (ENG) : Clone a repository:
1. (FRA) : Cloner un dépôt:

git clone <repository_url> example : git clone https://github.com/username/holbertonschool-zero_day.git

2. (ENG) : Create a new file:
2. (FRA) : Créer un nouveau fichier:

touch <filename>

3. Add the file to the staging area / Ajouter le fichier à la zone de transit:

git add <filename>

4. (ENG) : Commit changes with a message:
4. (FRA) : Valider les modifications avec un message:

git commit -m "Your commit message"

5. (ENG) : Push changes to the remote repository:
5. (FRA) : Transférer les modifications vers le référentiel distant:

git push origin <branch_name>

6. (ENG) : Pull updates from the remote repository:
6. (FRA) : Extraire les mises à jour du référentiel distant:

git pull origin <branch_name>

## Advanced Git Features / Fonctionnalités avancées de Git

1. (ENG) : Create a new branch:
1. (FRA) : Créer une nouvelle branche:

git checkout -b <branch_name>

2. (ENG) : Switch between branches:
2. (FRA) : Basculer entre les branches:

git checkout <branch_name>

3. (ENG) : Merge branches:
3. (FRA) : Fusionner les branches:

(ENG) : First, switch to the branch you want to merge into (usually main), then run:

(FRA) : Tout d’abord, passez à la branche dans laquelle vous souhaitez fusionner (généralement principale), puis exécutez:

git merge <branch_name>

4. (ENG) : Resolve merge conflicts: If there are conflicts during the merge, Git will prompt you to resolve them manually by editing the conflicting files:
4. (FRA) : Résoudre les conflits de fusion : s'il y a des conflits lors de la fusion, Git vous demandera de les résoudre manuellement en modifiant les fichiers en conflit.

5. (ENG) : Delete a branch:
5. (FRA) : Supprimer une branche:

(ENG) : Once a branch is no longer needed, you can delete it using:

(FRA) : Une fois qu'une branche n'est plus nécessaire, vous pouvez la supprimer en utilisant:

git branch -d <branch_name>

## Collaboration on Git / Collaboration sur Git

(ENG) : When working on a project with multiple contributors:

(FRA) : Lorsque vous travaillez sur un projet avec plusieurs contributeurs:

- (ENG) : Fork the repository: Create a personal copy of the project on GitHub.
- (FRA) : Forker le dépôt : Créez une copie personnelle du projet sur GitHub.    

- (ENG) : Clone the forked repository to your local machine.
- (FRA) : Clonez le référentiel forké sur votre machine locale.    

- (ENG) : Make changes and commit them.
- (FRA) : Apportez des modifications et validez-les.

- Create a pull request (PR) to propose changes to the original repository.

- Follow these guidelines to ensure smooth collaboration:

    1. Pull updates frequently to stay synced with the main repository.
    2. Keep your commits small and focused on specific features or fixes.
    3. Write detailed commit messages to explain your changes clearly.

## Good Practices / Bonnes pratiques

- (ENG) : `Commit often`: Make frequent commits to save your progress and track changes.
- (FRA) : `Commitez souvent`: effectuez des validations fréquentes pour enregistrer votre progression et suivre les modifications.

- (ENG) : `Write meaningful commit messages`: Use the imperative mood and explain the “why” of the change, not just the “what”.
- (FRA) : `Écrivez des messages de validation significatifs`: utilisez le mode impératif et expliquez le « pourquoi » du changement, pas seulement le « quoi ».

- (ENG) : `Keep your README.md up to date`: This is your project's documentation, and it should reflect its current state.
- (FRA) : `Gardez votre README.md à jour`: il s'agit de la documentation de votre projet, et elle doit refléter son état actuel.

- (ENG) : `Use .gitignore`: Exclude files that shouldn't be tracked (e.g., system files, sensitive data, and build files).
- (FRA) : `Utiliser .gitignore`: excluez les fichiers qui ne doivent pas être suivis (par exemple, les fichiers système, les données sensibles et les fichiers de build).

## Conclusion

(ENG) : By completing this project, you will have a solid understanding of source code management and will be able to use Git and GitHub effectively to manage your code and collaborate on projects.

(FRA) : En complétant ce projet, vous aurez une solide compréhension de la gestion du code source et serez en mesure d'utiliser Git et GitHub efficacement pour gérer votre code et collaborer sur des projets.

## Authors / Auteurs

- Lucas Niel - @Lucas Niel
