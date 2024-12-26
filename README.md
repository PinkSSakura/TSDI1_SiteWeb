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
   bash
   cd path/to/your/directory
3. **Create a new directory for your repositor** 
    mkdir my-repo
    cd my-repo
4. **Initialize a new Git repository**
    git init

## Cloning an Existing Repository

1. Use the **git clone** command followed by the repository URL:
    git clone https://github.com/username/repository.git

## Updating the Repository

1. **Navigate to your repository**
    cd path/to/your/repository
2. **Pull the latest changes**
    git pull origin main

## Adding files

1. **Create or edit** files in your repository.
2. **Stage the files you want to add**
    git add filename1 filename2
    git add .

## Deleting files

1. **Delete file from local directory**
    rm filename
2. **Stage the deletion**
    git add filename

## Save Changes

1. **Commit with a message for clafication**
    git commit -m "Your commit message here"
2. **Pushing Chanegs**
    git push origin main
