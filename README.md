# Demo-cero

## Programmer

## Guide 01

### Learning objetives

1.  CLI (Command Line Interface) and GUI (Graphical User Interface)
2.  VCS (Version Control System) and VCH (Version Control Hosting)
3.  Repository
4.  Git basics
5.  Installation
6.  Config
7.  Commands

    - $ git clone <REPO_URL>
    - $ git add
    - $ git commit
    - $ git push

8.  Markdown file and syntax
9.  README file

### 1. TERMINAL

a text-based user interface (UI) used to run programs, manage computer files and interact with the computer.

#### Terminal commands

    - pwd (path) ¿where I am?
    -ls (list) file list
    -clear (limpiar)clean terminal
    -mkdir (make directory) create new folder
    -exit (exit) exit

### 2. GIT

A version control system (VCS) tracks changes to a file or set of files over time, and a repository contains all of your project's files and each file's revision history. You can discuss and manage your project's work within the repository.

#### Intallation

1.  https://git-scm.com/ and download for windows
2.  open terminal and registrate, command
    - $ git config --global user.name "name" - $ git config --global user.email email@example.com

#### Commands

    - git help (Help)
    - git version -- v
    - git path

These are common Git commands used in various situations:

    - clone  (Clone a repository into a new directory)
    -init   (Create an empty Git repository or reinitialize an existing one)

work on the current change :

    -add (Add file contents to the index)
    -mv (Move or rename a file, a directory, or a symlink)
    -restore (Restore working tree files)
    -rm (Remove files from the working tree and from the index)

examine the history and state:

    -bisect (Use binary search to find the commit that introduced a bug)
    -diff (Show changes between commits, commit and working tree, etc)
    -grep (Print lines matching a pattern)
    -log (Show commit logs)
    -show (Show various types of objects)
    -status (Show the working tree status)

grow, mark and tweak your common history:

    -branch (List, create, or delete branches)
    -commit (Record changes to the repository)
    -merge (Join two or more development histories together)
    -rebase (Reapply commits on top of another base tip)
    -reset (Reset current HEAD to the specified state)
    -switch (Switch branches)
    -tag (Create, list, delete or verify a tag object signed with GPG)

collaborate (see also: git help workflows) :

    -fetch (Download objects and refs from another repository)
    -pull (Fetch from and integrate with another repository or a local branch)
    -push (Update remote refs along with associated objects)

#### How to import a repository?

Step one clone the repository with command **git clone - URL HTTP**
step two execute command **git branch** and done

#### How to update a repository?

Step one, make sure the local files are up to date **git status**
step two, run **git add name file\* to add the file
step three, **git commit** to add comments
step four, **git push\*\* to upload
