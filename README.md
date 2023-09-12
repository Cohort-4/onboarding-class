## Basic Command Line Tools 

`cd`:  Change directory.

`ls` (Unix-like) or `dir` (Windows): 
List files and directories in the current directory.

`pwd` (Unix-like) or `echo %cd%` (Windows): Print the current working directory.

`mkdir`: Create a new directory.

`touch` (Unix-like) or `echo > filename` (Windows): Create an empty file.

`rm` (Unix-like) or `del` (Windows): Remove files and directories.

`mv` (Unix-like) or `move` (Windows): Move or rename files and directories.

`cp` (Unix-like) or `copy` (Windows): Copy files and directories.


## Git
Git is a powerful version control system that helps you track 
changes in your code and collaborate with others.

### Common Basic git commands

`git init` 

`git status`

`git add .`

`git commit -m "commit message"`

`git remote add origin {repo_url}`

`git push -u origin master`


### Basic git commands
`git init` : Initializes a new Git repository in the current directory.

`git clone {repository_url}`: Creates a copy of a remote Git repository on your local machine.

`git add .` or  `git add {files(s)}`: Stages changes for commit. You can specify individual files or use '.' to stage all changes.

`git commit -m "{commit message}"` : Commits the staged changes to the repository with a descriptive message.

`git status`:  Shows the status of your working directory, including untracked files and changes ready to be committed.

`git log`: Displays a history of commits in the current branch, including commit messages, authors, and timestamps.

`git branch`: Lists all branches in the repository and highlights the current branch.

`git checkout {branchname}`: Switches to a different branch. You can also use this command to create a new branch.

`git merge {branchname}`: Combines the changes from one branch into the current branch.

`git pull`: Fetches changes from a remote repository and merges them into the current branch.

`git push`: Pushes your local changes to a remote repository.

`git remote -v`: Lists all remote repositories configured for the current project.

`git fetch`: Downloads changes from a remote repository but does not merge them into your local branch.

`git reset {file}`: Unstages changes in the specified file, or you can use --soft, --mixed, or --hard options to reset commits.

`git rm {file}`: Removes a file from the working directory and stages the deletion for the next commit.

`git stash`: Temporarily saves changes that are not ready to be committed, allowing you to switch branches or perform other operations.

`git tag {tagname}`: Creates a new tag for a specific commit, often used for marking releases.

`git remote add {name} {url}`: Adds a new remote repository with a specified name and URL.

name can be origin 

`git --help`  or  `git <command> --help` for more detailed information on each command.









