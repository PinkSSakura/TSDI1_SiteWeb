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
   