# A simple Python UDP Socket based Calculator

Welcome, this is an example project of the class assignment, below are instructions and explanations on how to get started with git and get your code on Github.

__to get your own code on Github check the [How to get your code on Github section](##How-to-get-your-Code-on-Github), but you can still skim through there's a lot of other useful info.__

# Introduction

## What is Git?
Git is a type of version control system(VCS), it is used for tracking the changes that are made to computer files, and coordinating work on those files among many people.

__whats is a version control system(VCS)__:it is a  tools that helps a software team manage changes to source code over time.

Version control software keeps track of every modification to the code in a special kind of database. If a mistake is made, developers can turn back the clock and compare earlier versions of the code to help fix the mistake while minimizing disruption to all team members.

It is primarily used for source code management in software development, but it can be used to keep track of changes in any set of files.

__what is a repo?__:
A software __repository__, known as a "repo" for short, simply means a storage location, it is a storage location from which software packages may be retrieved and installed on a computer.

__what is a remote repo?__:
A remote repo simply refers to a repository that is hosted on another computer/server, or hosting service such as Github, and Bitbucket.

__in git your repo is the .git folder in your project folder(working directory) it is called a local repo because it's located on your (local)machine__

### How does Git work?

Git is an example of a DVCS (Distributed Version Control System). Distributed means that everybody's copy of the project is also a repository that contains the full history of all changes.

## What is Github?
GitHub is a web-based hosting service for version control using git. It is mostly used for computer code. It offers all of the distributed version control and source code management functionality of Git as well as adding its own features.

# Git Basics

## How to get Git
To install git on your computer, follow the following instructions for your Operating System

- __Linux and Unix__: you can install Git on Linux using the preferred package manager of your Linux distribution. You can find installations instructions for your linux distribution [here](https://git-scm.com/download/linux)
- __Windows__: Click [this link](https://git-scm.com/download/win) to download the latest version for Windows.
- __Mac OS__: Click [this link](https://git-scm.com/download/mac) to download the latest version for Mac OS.

## How to Get Started with Git
Welcome to the world of git. Once you've installed git you can checked whether it was properly installed by typing `git`in your command line or terminal, it will show you a list of sub-commands, this means git is now installed on your computer and you can start creating repositories, if you get an error then install git using the links above.

- __what to do after installing__: you can do some important configuration after installing git.
	+ set your email address
		* `git config --global user.email "myemail@email.com"`
	+ set your user name
		* `git config --global user.name "myusername"`

- __create(initialize) a repo__: you can turn any folder/directory on your computer to a git repository by navigating to the folder in your command line/terminal and typing the following:

	`git init`

- __copy(clone) a repo__: cloning a repository means exactly what it suggests, it creates copies a remote repository to your computer,  to do this you need the URL of the repo you want to clone.

**For example** to clone this repo, navigate to the folder you would like to clone it into through your command line or Terminal(Bash), and use the `git clone` command  like this:

	git clone https://github.com/dbugshe2/simple-python-udp-socket-calculator

and it will create a folder called `simple-python-udp-socket-calculator` containing all the files in this repo.


- __working with remote repos__: a remote repo is simply a copy of a local repo, on another computer that a local repo is linked to, and one project can have many different remote repos.
If you `clone` a remote repo, then the repo is added by default as one of your remote repos.

## How to get your Code on Github
Suppose you have a folder `work` containing your programs and you would like to put it on GitHub.

1. __install git__ You must have git installed (you can find links above)

2. __Create a local repo__ on your computer, open a command line, and navigate to the `work` folder, and make it a git repo by typing the command

3. __Get a Github account__ Sign-up on GitHub if you haven't. [Click here to got to the registration page](https://github.com/join) (Open this in another tab)
4. __Create a github repo__ create a repo by following these steps.
	- click on the `+` icon at the top right and select 'new repository'<br>
![Image](new-repo.png?raw=true)
	- On the new repo page enter a name for the repo, seperating each word in the name with a hyphen `-` (all other information are optional)<br>
![Image](repo-name.png?raw=true)
	- Finally Click the `Create repository` button<br>
![Image](create-repo-button.png?raw=true)
5. __link(add) your remote GitHub repo to the local one__: Now add your GitHub repo as a remote repo of the local repo you just initialized, using the `remote add` command as follows:
	
```git remote add origin https://github.com/dbugshe2/sample-repo.git
```	
	- the word 'origin' is the name we chose to call the remote repo (you can name it anything you want)
	- the url that follows is the url of the remote repo, which you can find on the repo page after you have created it (like the screenshot below):<br>
	
![Image](repo-url.png?raw=true)

You can always check what remote repos you have by typing:
	
```git remote -v
```

### How to Send(Push) Your Project to GitHub

Now that you have a repository cloned or initialized, you can commit file version changes to it. The following example assumes you have set up a project at /path/to/project. The steps being taken in this example are:

- Change directories to /path/to/project
- Assuming your `work` folder has these following files: 
	+ server.py
	+ client.py
- git add both documents to the repository staging area
- Create a new commit with a message describing what work was done in the commit
	


	

## more Information


### Best Online Resources and Books for Learning about Git

- [Atlassian Git Tutorial](https://www.atlassian.com/git/tutorials)

__work in progress__