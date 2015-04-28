# Homework

In this homework assignment, you will be able to share your work on GitHub.  

## What is GitHub?

GitHub is a social network for developers. It allows anyone to create repositories (or projects)
and share them with others.

Git is a version control tool that allows you to manage repositories.

Repositories are made up of:

- commits
  - these are like snapshots of your entire project at some point in time.
- branches
  - branches are labels for commits. They are how we reference a snapshot and the snapshots that precede it.
  - typically each feature of a project will have its own branch.
- remotes
  - these are just links to other copies of your project.

## Create a GitHub Account

Please visit https://github.com/ and login, or sign up for an account if you
do not have one.

## Create a New Repository

Visit <https://github.com/new>, enter a repository name and click the
green "create repository" button.

Give it a name that effectively describes the project you are working on.

## Copy the Repository to your Machine

    $ git clone https://github.com/your-user-name/your-project-name.git

##  Add your work 

Copy your html file(s) into the newly created folder.

Back in the terminal, you need to start tracking these files by first changing directory
to the project:

    $ cd your-project-name 
    $ git status
    #=> Should show untracked files

    $ git add .
    $ git status
    #=> Should show added files

## Take a Snapshot

i.e make a commit, with a message describing your changes.

    $ git commit -m "Add semantic HTML"

## Push your changes to GitHub

    $ git push origin master

`master` is the name of the branch you want to share. `origin` is a nickname for your local
repository's remote. It is short for `git@github.com:your-user-name/your-project-name.git`

## Did it Work?

If you visit your project on GitHub, do you see the changes you just added? If so, then yes!
You have now shared your work on GitHub!




