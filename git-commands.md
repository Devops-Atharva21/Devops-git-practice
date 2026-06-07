## Setup & Config

### git --version
Purpose: Displays installed Git version

Example:
git --version

### git config --global user.name
Purpose: Sets Git username

Example:
git config --global user.name "Atharva K"

### git config --global user.email
Purpose: Sets Git email

Example:
git config --global user.email "devopatharva29@gmail.com"

##Basic Workflow

### git init
Purpose: Creates a new Git repository

Example:
git init

### git add
Purpose: Adds files to staging area

Example:
git add git-commands.md

### git commit
Purpose: Saves staged changes

Example:
git commit -m "Initial commit"

##Viewing Changes

### git status
Purpose: Shows repository status

Example:
git status

### git log
Purpose: Shows commit history

Example:
git log

### git log --oneline
Purpose: Shows compact commit history

Example:
git log --oneline

### git diff
Purpose: Shows changes before staging

Example:
git diff

### git show
Purpose: Shows commit details

Example:
git show

### git branch
Purpose: Lists branches

Example:
git branch

###
| Command                     | Purpose (One Line)                                                      |
| --------------------------- | ----------------------------------------------------------------------- |
| `git branch`                | Lists all branches in the repository and highlights the current branch. |
| `git branch feature-1`      | Creates a new branch named `feature-1`.                                 |
| `git switch feature-1`      | Switches to the existing `feature-1` branch.                            |
| `git checkout feature-1`    | Switches to the `feature-1` branch (older method).                      |
| `git checkout -b feature-2` | Creates a new branch `feature-2` and switches to it in one command.     |
| `git switch -c feature-2`   | Creates a new branch `feature-2` and switches to it (modern method).    |
| `git branch -d feature-2`   | Deletes the `feature-2` branch if it has already been merged.           |

