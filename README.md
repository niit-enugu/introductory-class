# GIT Commands

## Content
- [Defination](#what-is-git)
- [Prerequisits](#prerequisits)
- [Git Initalization](#git-initalization)
- [Checking git status](#checking-git-status)
- [Staging your files](#staging-your-files)



## What is GIT?
Git is an **open source** distributed version control system


## Prerequisits
To use GIT, you are expected to have an updated version of the software on your operating system
To download go to the [git website]() and download the version for your operating system.

## Git Initalization
To initialize a git repository we use the `git init` command. To do this, 
1. Navigate to your working directory
```
cd working-dir
```
2. Type the command `git init` to initialize the dir into a repository
```
git init
```

## Checking git status
To check the status of your git repository, you can use the command `git status` as seen below
```
git status
```

## Staging your files
Staging or adding your file is the term used to describe the process of making git track your files,
this involves moving the files from the workspace to the staging area. To do this, use `git add filename` command to add a single file, `git add file1 file1` to add multiple files, and `git add .` or `git add -A` to add all files. Example
 ```
 git add index.html
 ```
 ```
 git add index.html style.css
 ```
 ```
 git add .
 ```