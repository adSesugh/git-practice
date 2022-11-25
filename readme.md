1. initialize a git
    `git init`

2. create file via commandline
    `touch <file_name>.<extension>
3. add content via commandline
    `echo "<content>" >> <file_name> 
4. add file to git
    `git add <file_name>` - add a specific file to git
    `git add .` -  add all downward files in the current directory to git
5. commit changes
    `git commit <flags|-a,-m>`
        - `git commit -a` - this open up all files changes of the staging area in an editor for you to decide which files you actually want to commit should in case you don't want to commit all changes in staging area
        - `git commit -m` - go ahead commit all files/changes in staging area with a description. for example `git commit -m "My first commit"`
6. To create branch 
    `git branch <branch_name>`
7. To switch between branches
    `git checkout <branch_name>`
9. To verify a commit
    `git log`
10. To View changes done in a commit
    `git show <commit_hash>`
11. To display status of git
    `git status`

To do
- `git remote add origin` - to add remote repository to your local 
- `git push` - push local commit to remote reposity
- `git pull` - pull remote repository to local pc
- `git rebase`  - to squash a multiple commits
- `git merge`   - to merge branches
- `git clone` - 
repository to enable push to github

