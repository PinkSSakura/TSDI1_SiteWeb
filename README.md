# Languages
1. [English](#english)
2. [Français](#francais)

# English
# Git Repository Management Guide

This guide provides step-by-step instructions for creating a Git repository, updating it, adding files, and deleting files using the command line.

## Table of Contents
1. [Creating a New Repository](#creating-a-new-repository)
2. [Cloning an Existing Repository](#cloning-an-existing-repository)
3. [Updating the Repository](#updating-the-repository)
4. [Adding Files](#adding-files)
5. [Deleting Files](#deleting-files)
6. [Committing Changes](#committing-changes)
7. [Pushing Changes](#pushing-changes)
8. [Resolving Conflicts](#resolving-conflicts)

## Creating a New Repository

1. **Open your command line interface** (Command Prompt, PowerShell, Terminal, etc.).
2. **Navigate to the directory** where you want to create your repository:
   ```bash
   cd path/to/your/directory
   ```
3. **Create a new directory for your repository** :
   ```bash
   mkdir my-repo
   cd my-repo
   ```
4. **Initialize a new Git repository** :
   ```bash
   git init
   ```

## Cloning an Existing Repository

1. Use the **git clone** command followed by the repository URL:
   ```bash
   git clone https://github.com/username/repository.git
   ```

## Updating the Repository

1. **Navigate to your repository** :
   ```bash
   cd path/to/your/repository
   ```
2. **Pull the latest changes** :
   ```bash
   git pull origin main
   ```

## Adding Files

1. **Create or edit** files in your repository.
2. **Stage the files you want to add** :
   ```bash
   git add filename1 filename2
   git add .
   ```

## Deleting Files

1. **Delete file from local directory** :
   ```bash
   rm filename
   ```
2. **Stage the deletion** :
   ```bash
   git add filename
   ```

## Committing Changes

1. **Commit with a message for clarification** :
   ```bash
   git commit -m "Your commit message here"
   ```

## Pushing Changes

1. **Push your changes to the remote repository** :
   ```bash
   git push origin main
   ```

---
# Français
# Guide de Gestion de Référentiel Git

Ce guide fournit des instructions étape par étape pour créer un référentiel Git, le mettre à jour, ajouter des fichiers et supprimer des fichiers en utilisant la ligne de commande.

## Table des Matières
1. [Créer un Nouveau Référentiel](#créer-un-nouveau-référentiel)
2. [Cloner un Référentiel Existant](#cloner-un-référentiel-existant)
3. [Mettre à Jour le Référentiel](#mettre-à-jour-le-référentiel)
4. [Ajouter des Fichiers](#ajouter-des-fichiers)
5. [Supprimer des Fichiers](#supprimer-des-fichiers)
6. [Enregistrer les Modifications](#enregistrer-les-modifications)
7. [Pousser les Modifications](#pousser-les-modifications)
8. [Résoudre les Conflits](#résoudre-les-conflits)

## Créer un Nouveau Référentiel

1. **Ouvrez votre interface de ligne de commande** (Command Prompt, PowerShell, Terminal, etc.).
2. **Naviguez jusqu'au répertoire** où vous souhaitez créer votre référentiel :
   ```bash
   cd chemin/vers/votre/dossier
   ```
3. **Créez un nouveau dossier pour votre référentiel** :
   ```bash
   mkdir mon-repo
   cd mon-repo
   ```
4. **Initialisez un nouveau référentiel Git** :
   ```bash
   git init
   ```

## Cloner un Référentiel Existant

1. Utilisez la commande **git clone** suivie de l'URL du référentiel :
   ```bash
   git clone https://github.com/utilisateur/referentiel.git
   ```

## Mettre à Jour le Référentiel

1. **Accédez à votre référentiel** :
   ```bash
   cd chemin/vers/votre/referentiel
   ```
2. **Récupérez les dernières modifications** :
   ```bash
   git pull origin main
   ```

## Ajouter des Fichiers

1. **Créez ou modifiez** des fichiers dans votre référentiel.
2. **Mettez en scène les fichiers que vous souhaitez ajouter** :
   ```bash
   git add fichier1 fichier2
   git add .
   ```

## Supprimer des Fichiers

1. **Supprimez le fichier du répertoire local** :
   ```bash
   rm fichier
   ```
2. **Mettez en scène la suppression** :
   ```bash
   git add fichier
   ```

## Enregistrer les Modifications

1. **Faites un commit avec un message pour clarifier les modifications** :
   ```bash
   git commit -m "Votre message de commit ici"
   ```

## Pousser les Modifications

1. **Envoyez vos modifications vers le référentiel distant** :
   ```bash
   git push origin main
   ```
