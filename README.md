# This is a repo to learn git


---

### For setting up git initally
`git config --global user.name"My Name" ` - github username

`git config --global user.email"someemail@gmail.com"`

`git config --list`

`git clone <link_of_repo>`



---


### comman git commands
`git status` - to cheak the status of the changes

`git add .`

`git commit -m"<message>"`

`git push <origin> main ` - push the code to the github 

`git pull <origin> main` - any latest changes done in git hub can be pulled here 

`git log` - print all the recent commits


---

### init command
- `git init - used to initialize a git repo`  - use it when ever you create a new dir inside the local machine
- `git remote add origin<-link->`
- `git remove -v `(to verify remote)
- `git branch `(to check branch)
- `git push -M <main>` (to rename branch)
- `git push origin main `
- `git push -u origin  main ` \\ to set upstream - used to always push to main 


---


### Branch commands
- `git branch`                              (to cheak branch)
- `git branch -M main `                     (to rename branch)
- `git checkout <-branch name->`            (to navigate)
- `git checkout -b <-new branch name->`     (to create new branch)
- `git branch -d <-branch name->`           (to delete a branch)

---

### merge branch 
1. way 1
   - `git diff <-branch name->`       (to compare commits, branches, files & more)
   - `git merge <-branch name->`      (to merge 2 branch)

2. way 2
    create a **PR** (pull request)




---




### undoing changes
1. case 1: staged changes 
    - `git reset <-file name->`
    - `git reset`
2. case 2: commited changes(for one commit)
    - `git reset  HEAD~1`               - reset to previous changes
3. case 3: commited cahnges (for many commits)
    - `git reset <-commit hash->`          - hash code is in github or use (git log) in terminal
    - `git reset --hard <-commit hash->`   - to remove the changes in local machine


---

### types of files 
1. untracked   - new files that git does not yet track
2. modilfied   - changed
3. staged      - file is ready to be committed 
4. unmodilfied - unchanged

---