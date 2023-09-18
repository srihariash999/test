git --> version control system.

github --> website (based on git). Basically, social media for code.

1. Stage (select things you want to commit)
2. Commit (Write a message on what the changes are about.)
3. Push (push the changes to the remote)

U => "Untracked" (git does not know this file yet)
A => "Added" - File is added (or staged) for commit.
M => "Modifiled" - A file known to git is modified.

// TERMINAL COMMANDS

### For Staging

- for adding all files

  git add .

- for adding only file required

  git add <path to file name> (folder/file_name)

### For Committing

git commit -m '<enter your commit message here.>'

NOTE: be descriptive about your commit, but don't write an essay.

### For Pushing (to remote)

git push origin <branch_name>

### For checking which branch you are on

git branch

NOTE : 'press q to exit'
