# Git Commands Cheat Sheet

## 1. Basic Commands

- **`git help`**: Take help from the Git help section for different commands and other errors.
- **`git config`**: To set the basic configurations on Git like name and email.
- **`git config --global user.name " " `**: Sets configuration values for your username on git.
- **`git config --global user.email " " `**: Sets configuration values for your user email on git.
- **`git config --global color.ui true`**: To see different colors on the command line for different outputs.
- **`git init`**: To create a local git repo in our desired folder.
- **`git status`**: To see what's changed since the last commit. It shows all the files that have been added and modified and are ready to be committed, and files that are untracked.

## 2. Adding and Committing Changes

- **`git add Readme.txt`**: To add a file `Readme.txt` to the staging area to track its changes.
- **`git commit -m " "`**: To commit our changes (taking a snapshot) and provide a message to remember for future reference.
- **`git log`**: To check the history of commits for our reference.
- **`git add`**: To add a specific list of files to the staging area.
- **`git add --all`**: To add all files of the current directory to the staging area.
- **`git add *.txt`**: To add all text files of the current directory to the staging area.
- **`git add docs/*.txt`**: To add all text files of a particular directory (`docs`) to the staging area.
- **`git add docs/`**: To add all files in a particular directory (`docs`) to the staging area.
- **`git add "*.txt"`**: To add text files of the entire project to the staging area.
- **`git diff`**: To figure out what changes you made since the last commit.

## 3. Undoing Changes

- **`git reset head license`**: To undo the staging of the file that was added in the staging area.
- **`git checkout --license`**: To discard all changes since the last commit of the file.
- **`git commit -a -m "Readme.md"`**: To add any of our tracked files to the staging area and commit them by providing a message to remember.
- **`git reset --soft HEAD^`**: To undo the last commit and bring the file to the staging area.
- **`git reset --hard HEAD^`**: To undo the last commit and remove the file from the staging area as well (in case we went horribly wrong).
- **`git reset --hard HEAD^^`**: To undo the last 2 commits and all changes.

## 4. Working with Remotes

- **`git remote add origin https://github.com/ayushkjha24/Git-and-Github.git`**: These commands make a bookmark that signifies that this particular remote refers to this URL. This remote will be used to pull any content from the directory and push our local content to the global server.
- **`git remote add <address>`**: To add new remotes to our local repo for a particular git address.
- **`git remove rm`**: To remove a remote from our local repo.
- **`git push -u origin master`**: To push all the contents of our local repo that belong to the master branch to the server (Global repository).
- **`git clone https://github.com/ayushkjha24/Git-and-Github.git`**: To clone or make a local copy of the global repository in your system (git clone command downloads the repository and creates a remote named `origin` which can be checked by the command `git remote -v`).

## 5. Branching

- **`git branch Testing`**: To create a new branch named Testing.
- **`git branch`**: To see all the branches present and current branches that we are working on.
- **`git checkout Testing`**: To switch to branch Testing from the master branch.
- **`git merge Testing`**: To merge the Testing branch to the master branch.
- **`git branch -d`**: To delete the Testing branch.
- **`git checkout -b admin`**: To create a new branch named admin and set it as the current branch.
- **`git branch -r`**: To look at all the remote branches.
- **`git branch -D Testing`**: To forcefully delete a branch without making commits.

## 6. Tags

- **`git tag`**: To see the list of available tags.
- **`git checkout v0.0.1`**: To set the current tag to `v0.0.1`.
- **`git tag -a v0.0.3 -m "v0.0.3"`**: To create a new tag.
- **`git push --tags`**: To push the new tag to the remote repository.

## 7. Fetching and Stashing

- **`git fetch`**: To fetch down any changes from the global repository to the current repository.
- **`git stash`**: To move staged files to the stash area which is present in the staging area.
- **`git stash pop`**: To get back the files that are present in the stash area.
- **`git stash clear`**: To clear the stash folder.

## 8. Rebasing

- **`git rebase`**: Three tasks are performed by git rebase:
  1. Move all changes to the master which are not in `origin/master` to a temporary area.
  2. Run all origin master commits.
  3. Run all commits in the temporary area on top of our master one at a time, so it avoids merge commits.

## 9. Miscellaneous

- **`git --version`**: Used to show the current version of git.
- **`mkdir store`**: Create a directory if not created already.
- **`cd store`**: To go inside the directory and work on its contents.
