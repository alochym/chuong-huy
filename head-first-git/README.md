# HEAD FIRST GIT

1. Create a root folder - startOver
1. Change to a root folder - cd startOver
1. Initialize git - git init
1. Create a git ignore file(help to ignore file which to be added to git repo) - touch .gitignore

## Git conffig

1.  Config Fullname - git config --global user.name "Do Nguyen Ha"
1.  Config Email - git config --global user.email "donguyenha@live.com"

### Git branch

1. Branches allow you to keep your changes completely independent of one another.
1. Git branches can fork off and grow in parallel.
1. Create a branch - git branch alochym.
1. Switch to use a branch:
   1. git checkout alochym -> old git version.
   1. git switch alochym.
1. List all branches - git branch.
1. Delete branch - git branch -d alochym.

### Git merge

1. **Bringing the work that was done in separate branches together**.
1. Merging in Git typically involves two branches:
   1. The branch that you are on (we’ll refer to this as the “proposer”)
   1. The branch you wish to merge or “mix” in (we’ll call this the “proposee”).
1. Example:
   1. There are two branch: bake-cake and prepare-icing.
   1. You are on bake-cake branch - git switch bake-cake.
   1. You are going to merge prepare-icing to bake-cake - git merge prepare-icing.

### Git log

1. To visualize a the commits history and list all git commits in **current branch** - git log.
1. To navigate the git log we use up/down arrow key.
1. To quit the git log we use "q" key.
1. To make human read the git log - git log --pretty=oneline --abbrev-commit.
1. To navigate to specific commit of the git log - git log < commit-hash >.
1. To view commit history of file in the git log - git log < file-name >. 

### Git diff

1. **To track the difference between the changes made on a file**.
1. How it works - **compares the version of Git's index with the version of the file in the working directory**.
