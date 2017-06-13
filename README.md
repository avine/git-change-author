# git-change-author
Change git author for all commits

## Installation

Change the mode of the following files.

```shell
chmod +x auth.sh
chmod +x change.sh
chmod +x push.sh
```

Open `auth.sh` and `change.sh` and change the name and email acording to your needs.

### Usage

Put the folder `git-change-author` in the same parent folder of your project.

Open your project folder in a terminal (where your `.git` folder is located).

Execute the following commands.

```shell
../git-change-author/auth.sh # Set the git author of current workspace
../git-change-author/change.sh # Change the git author of the entire history
../git-change-author/push.sh # Push the new git history
```
