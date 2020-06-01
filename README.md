# Introduction
These are some useful git commands to get started to use git. 


1. Start a new project locally

`git init`

The output is: `Initialized empty Git repository in /Users/rishabhparekh/code/essential-git/.git/`

2. Add files to the repo locally. 

git remote add origin git@rishabh:rishabh-parekh/covid.git

`git add *`

3. Create a remote (github) repo

Go to the browser, http://www.github.com and create a new repo

![Git Create Repo ](./images/new-repo.png "Create Repo")

5. Connect Remote to local

`git remote add origin git@rishabh:rishabh-parekh/essential-git.git`

4. Upload changes from local to github

Every time I make changes, I can commit and push. 

`git commit -am “Initial Readme and images committed”`
`git push origin master`

5. If someone else makes a change and I want to accesss it
`git pull origin master`

6. How to check the status
`git status` (for local status)
`git status remote` (for remote status)
