## What is GIT & GitHub

**What is GIT?**

Open source distributed version control system.

**What is Distributed Version Control?**

Peer-to-peer approach to version control, as opposed to the client–server approach of centralized systems. Distributed revision control synchronizes repositories by transferring patches from peer to peer. No single central version of the codebase; each user has a working copy and the full change history.

Put simply, each person in a team has a copy of the project, edit their copy of the project and update a local database detailing a reason for their edits, this all being stored locally on their computer. Then pushed chanegs to a shared version, which is where GitHub comes in.

**What is GitHub?**

You are using GitHub to read this so you have a vague idea of what GitHub is, but for the sake of being thorough.

A place for to store and share the centralised version of the project. One can issue commands from the command line to perform most tasks.

## Install GIT

In ubuntu type `$ sudo apt install git-all` at the command line.

## Create a GitHub Account

Go to [GitHub](https://github.com/join) and sign up.

## Create a local GIT repository

Type the following at the command line.


`$ mkdir Projects` Make directory in home directory.

`$ cd Projects` Move to this directory.

`$ mkdir git-intial-setup` Make directory for your specific project, this one is called git-intial-setup.

Enter the directory for the specific project, and intitalise GIT.

``` 
$ cd LFS-Suckless
$ git init
```

Next we create a README.md in markdown using Neo-Vim and then look at how to update GIT and create a repository on GitHub.


