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

- `Source Code Management (SCM)`: The process of tracking and managing changes to software code.
- `Gestion du code source (GCS)`: Processus de suivi et de gestion des modifications apportées au code logiciel.

- `Git`: A distributed version control system that helps developers track code changes and collaborate on projects.
- `Git`: Un système de contrôle de version distribué qui aide les développeurs à suivre les modifications de code et à collaborer sur des projets.

- `GitHub`: A platform built on top of Git, used for hosting code, collaborating on repositories, and managing projects.
- `GitHub`: Une plate-forme construite sur Git, utilisée pour héberger du code, collaborer sur des référentiels et gérer des projets.

- `Branches`: Used to work on different versions of a project in parallel.
- `Branches`: Permet de travailler en parallèle sur différentes versions d'un projet.

- `Commits`: Snapshots of the repository's state at a particular time, containing changes made to the code.
- `Commits`: Instantanés de l'état du référentiel à un moment donné, contenant les modifications apportées au code.

## Resources / Ressources

(ENG) : Before starting, you should review the following resources:
(FRA) : Avant de commencer, vous devez consulter les ressources suivantes:

- Git : Resources to learn Git / Git : Ressources pour apprendre Git
- About READMEs / À propos des README
- How to write a Git commit message / Comment écrire un message de commit Git

### For advanced users / Pour les utilisateurs avancés:

- Learning branching / Apprendre le branchage
- Effective pull requests / Demandes de tirage efficaces

## Learning Objectives / Objectifs d'apprentissage

(ENG) : By the end of this project, you will be able to:
(FRA) : À la fin de ce projet, vous serez capable de :

- Explain source code management and why it's important. / Expliquez la gestion du code source et pourquoi c'est important.

- Define what Git and GitHub are and their differences. / Définir ce que sont Git et GitHub et leurs différences.

- Create and manage a repository. / Créer et gérer un référentiel.

- Write a README.md file for your project. / Écrire un fichier README.md pour votre projet.

- Commit changes and write meaningful commit messages. / Validez les modifications et rédigez des messages de validation significatifs.

- Push and pull code to/from GitHub. / Poussez et extrayez du code vers/depuis GitHub.

- Create and work with branches. / Créer et travailler avec des branches.

- Merge branches and resolve conflicts. / Fusionner les branches et résoudre les conflits.

- Collaborate on a project with multiple contributors. / Collaborer sur un projet avec plusieurs contributeurs.

- Understand which files should or should not appear in a repository. / Comprendre quels fichiers doivent ou ne doivent pas apparaître dans un référentiel.

## Requirements / Exigences

### General

    All commands should be executed via the command line.
    No GitHub web UI should be used, except for actions that can't be performed from the command line.
    You must provide:
        A README.md file at the root of the repository, describing the repository.
        A README.md file in the git/ folder, describing the purpose of this sub-project.

- Tools Needed / :

    Git: You should have Git installed on your system. Use the following command to install it on Ubuntu:

    bash

    sudo apt-get update
    sudo apt-get upgrade
    sudo apt-get install git

    Text Editor: You can use vim, nano, or any other text editor of your choice to write and edit files.

Installation

To get started with this project, clone the repository to your local machine:

bash

git clone https://github.com/username/holbertonschool-zero_day.git

Once cloned, navigate to the project directory:

bash

cd holbertonschool-zero_day

Basic Git Usage

The following are the basic commands you'll use to interact with Git:

    Clone a repository:

    bash

git clone <repository_url>

Create a new file:

bash

touch <filename>

Add the file to the staging area:

bash

git add <filename>

Commit changes with a message:

bash

git commit -m "Your commit message"

Push changes to the remote repository:

bash

git push origin <branch_name>

Pull updates from the remote repository:

bash

    git pull origin <branch_name>

Advanced Git Features

    Create a new branch:

    bash

git checkout -b <branch_name>

Switch between branches:

bash

git checkout <branch_name>

Merge branches:

First, switch to the branch you want to merge into (usually main), then run:

bash

git merge <branch_name>

Resolve merge conflicts: If there are conflicts during the merge, Git will prompt you to resolve them manually by editing the conflicting files.

Delete a branch:

Once a branch is no longer needed, you can delete it using:

bash

    git branch -d <branch_name>

Collaboration on Git

When working on a project with multiple contributors:

    Fork the repository: Create a personal copy of the project on GitHub.
    Clone the forked repository to your local machine.
    Make changes and commit them.
    Create a pull request (PR) to propose changes to the original repository.

Follow these guidelines to ensure smooth collaboration:

    Pull updates frequently to stay synced with the main repository.
    Keep your commits small and focused on specific features or fixes.
    Write detailed commit messages to explain your changes clearly.

Good Practices

    Commit often: Make frequent commits to save your progress and track changes.
    Write meaningful commit messages: Use the imperative mood and explain the “why” of the change, not just the “what”.
    Keep your README.md up to date: This is your project's documentation, and it should reflect its current state.
    Use .gitignore: Exclude files that shouldn't be tracked (e.g., system files, sensitive data, and build files).

## Conclusion

By completing this project, you will have a solid understanding of source code management and will be able to use Git and GitHub effectively to manage your code and collaborate on projects.
