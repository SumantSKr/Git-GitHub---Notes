# Git-GitHub---Notes
Git and GitHub Notes

# What is Git
Git is a version control system that is used to track changes to your files. It is a free and open-source software that is available for Windows, macOS, and Linux. Remember, GIT is a software and can be installed on your computer.

# What is GitHub
Github is a web-based hosting service for Git repositories. Github is an online platform that allows you to store and share your code with others. It is a popular platform for developers to collaborate on projects and to share code. It is not that Github is the only provider of Git repositories, but it is one of the most popular ones.

# Version Control System
Version control systems are used to manage the history of your code. They allow you to track changes to your files and to collaborate with others. Version control systems are essential for software development. Consider version control as a checkpoint in game. You can move to any time in the game and you can always go back to the previous checkpoint. This is the same concept in software development.

Before Git became mainstream, version control systems were used by developers to manage their code. They were called SCCS (Source Code Control System). SCCS was a proprietary software that was used to manage the history of code. It was expensive and not very user-friendly. Git was created to replace SCCS and to make version control more accessible and user-friendly. Some commong version control systems are Subversion (SVN), CVS, and Perforce.

# Learning Journey
**Git and Github are need of us for storing the code history.**
We will go in this jounney something like this:

Get the basics
Use it daily
Face the problems
Solve them
Learn more

# Install Git on your computer
To install Git, you can use command line or you can visit official website and download the installer for your operating system. Git is available for Windows, macOS, and Linux and is available at https://git-scm.com/downloads.

# Create an account on GitHub
Go to https://www.github.com and create an account just like you create on other social media or some app. Just click on Sign Up and fill in the details and done!

# Checking the Git Version on your Computer
Once you downloaded the Git on your computer you are ready to work with Git ( Version Control System ). As a first command you can type a to check the version of git on your computer.

*git --version*

# Repository
A repository is a collection of files and directories that are stored together. It is a way to store and manage your code. A repository is like a folder on your computer, but it is more than just a folder. It can contain other files, folders, and even other repositories. You can think of a repository as a container that holds all your code.

There is a difference between a software on your system vs tracking a particular folder on your system. At any point you can run the following command to see the current state of your repository:

<img width="300" height="217" alt="77634739ccd84c4a9887b1829d7212b04d8157bacfe6048d7174bd351d03ea23" src="https://github.com/user-attachments/assets/d2a4be58-cf61-4bf1-a8b6-0d4cbe9ae49e" />

**Checking Status**

*Git --status*

# configuration Settings
Github has a lot of settings that you can change. You can change your username, email and other settings. Whenever you checkpoint your changes, git will add some information about your such as your username and email to the commit. There is a git config file that stores all the settings that you have changed. You can make settings like what editor you would like to use etc. There are some global settings and some repository specific settings.

Let's setup your email and username in this config file. I would recommend you to create an account on github and then use the email and username that you have created.

*git config --global user.email "your-email@example.com"*
*git config --global user.name "Your Name"*

Now you can check your config settings:

*git config --list*

This will show you all the settings that you have changed.

# Creating a Repository
Creating a repository is a process of creating a new folder on your system and initializing it as a git repository. It's just regular folder to code your project, you are just asking git to track it. To create a repository, you can use the following command:

*git status*
*git init*

**git status** command will show you the current state of your repository. **git init** command will create a new folder on your system and initialize it as a git repository. This adds a hidden .git folder to your project.

# Commit
Used to **save  changes to the repository**. Record changes and make them permanent. 

<img width="1460" height="184" alt="b80b12df1d1ff125526f4b6a6c1b38af47ec407eca9c856cf88d92fb50444830" src="https://github.com/user-attachments/assets/7a14b621-e2f7-49f0-ab01-be1f150c0970"/>

When you want to track a new folder, you first use init command to create a new repository. Then you can use add command to add the folder to the repository. After that you can use commit command to save the changes. Finally you can use push command to push the changes to github. Of course there is more to it but this is the basic flow.

# Stage
Stage is a way to tell git to track a particular file or folder. You can use the following command to stage a file:

*git init*
*git add <file> <file2>*
*git status*

# Complete Git Flow
A complete git flow, along with pushing the code to github looks like this:

Here we are initializing the repository and adding a file to the repository. Then we can see that the file is now being tracked by git. Currently our files are in staging area, this means that we have not yet committed the changes but are ready to be committed.

# Commit

<img width="2920" height="2041" alt="9b7ee99d7c8c673847d56bd2573cc8de89d8b0bb0a0068efae66cfaebcf28ae7" src="https://github.com/user-attachments/assets/d0769542-f971-4201-afc4-b3d0a831130c" />


When you want to track a new folder, you first use init command to create a new repository. Then you can use add command to add the folder to the repository. After that you can use commit command to save the changes. Finally you can use push command to push the changes to github. Of course there is more to it but this is the basic flow.

# Stage
Stage is a way to tell git to track a particular file or folder. You can use the following command to stage a file:
