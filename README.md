# git-copy
Copy a root directory or file from one git repository to another with full history.

# Usage 
```
git-copy FROM-REPO#BRANCH TO-REPO#BRANCH ITEM [ITEM]...
```
If the branch is not present in the destintation repository then it will be created from the default branch.

For example to copy the README from this repository you would do the following:
```
git-copy https://github.com/bnwl/git-copy.git#master https://repo.test/user/project.git#master README.md
```
