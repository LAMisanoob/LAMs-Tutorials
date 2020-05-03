## What is GIT & GitHub

**What is GIT?**

Git is a free and open source distributed version control system designed to handle everything from small to very large projects with speed and efficiency.

**What is Distributed Version Control?**

Distributed version control systems (DVCS) use a peer-to-peer approach to version control, as opposed to the client–server approach of centralized systems. Distributed revision control synchronizes repositories by transferring patches from peer to peer. There is no single central version of the codebase; instead, each user has a working copy and the full change history.

Put simply, each person in a team has a copy of the project, they edit their copy of the project and update a local database with the reason for their edits all of this initially being stored locally on their computer. These are all then pushed up to a shared version, which is where GitHub comes in.

**What is GitHub?**

Beings that you are using GitHub to read this I imagine you already have a vague idea of what GitHub is, but for the sake of being thorough.

This is a place for to store and share the centralised version of the project. The benefits of GitHub is that one can issue commands from a command line shell. I shall undate this document further to have mnore information, though for now I feel this is enough.

## Install GIT

Realtively straightforward just go to the command line and type.

```
$ sudo apt install git-all
```

## Create a GitHub Account

Go to [GitHub](https://github.com/join) and sign up.

## Create a local GIT repository

This is where is gets slightly more complex for a beginner though still realtively straitforward.

One will neede to make a project directory in one's home directory.                                                                                                                                                                           
                                                                                                                                                                                                                                              
```                                                                                                                                                                                                                                           
$ mkdir Projects                                                                                                                                                                                                                              
```                                                                                                                                                                                                                                           
                                                                                                                                                                                                                                              
Enter this directory                                                                                                                                                                                                                          
                                                                                                                                                                                                                                              
```                                                                                                                                                                                                                                           
$ cd Projects
```

Then create a directory for you specific project, we shall call this one LFS-Suckless

```
$ mkdir LFS-Suckless
```

We now need to initialise GIT in this specific  project directory enter the directory and intitalise GIT.

``` 
$ cd LFS-Suckless
$ git init
```

Next we create a README.md in markdown using Neo-Vim and then look at how to update GIT and create a repository on GitHub.


