**# Git Commands and Explanations**
Repository Initialization
**git init**: Initializes a new Git repository in the current directory, allowing you to start tracking files.

**Configuring User Information**
**git config --global user.name "pushprajrana"**: Sets the global username for all future Git commits.
**git config --global user.email "pushprajrana789@gmail.com"**: Sets the global email address for all future Git commits.

**File Operations**
**vim hello-dosto.txt**: Opens the file hello-dosto.txt in the Vim text editor for editing.
**cat hello-dosto.txt**: Displays the content of hello-dosto.txt in the terminal, allowing you to read it.
**touch nibba.txt nibbi.txt**: Creates two new empty files named nibba.txt and nibbi.txt.

**Adding and Committing Files**
**git add nibbi.txt**: Stages the file nibbi.txt, preparing it to be included in the next commit.
**git commit -m "adding nibba nibbi"**: Commits the staged changes with a message describing what was done.
**git add nibba.txt**: Stages the file nibba.txt for the next commit.
**git commit -m "added new update file"**: Commits the changes to nibbi.txt with a message.
git add nibbu.txt: Stages the newly created file nibbu.txt for committing.
git commit -m "nibbu added": Commits the changes with a message indicating that nibbu.txt was added.

**Checking Status**
git status: Displays the current status of the working directory and staging area, indicating which files are tracked, untracked, modified, or staged.

**Removing Files**
rm hello-dosto.txt: Deletes the file hello-dosto.txt from the working directory.
git rm --cached nibba.txt: Removes nibba.txt from the staging area but keeps the file in the working directory.

**Branch Management**
git branch: Lists all branches in the repository and highlights the current branch you are on.
git checkout -b dev: Creates a new branch called dev and switches to it immediately.
git checkout master: Switches back to the master branch.
git checkout dev: Switches to the dev branch.
git checkout -b from-dev: Creates a new branch named from-dev and switches to it.

**Viewing Logs**
git log: Displays the full commit history for the repository, showing detailed information about each commit.
git log --oneline: Shows a condensed version of the commit history, displaying only the commit hashes and messages.

**Switching Branches**
git switch dev: Switches to the dev branch.
git switch master: Switches back to the master branch.

**Miscellaneous Commands**
git restore nibbi.txt: Restores the file nibbi.txt to its state as of the last commit, discarding any uncommitted changes.
