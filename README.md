# My Notes
Here I store notes and anything else I need to remember.

## Git/GitHub

### Create a new Repo

1. Got to GitHub and create a new repository -> Copy the link to that repository.
2. git remote add origin https://github.com/StefanSilver3/test_repo.git
3. go to folder where you have youre repo/code or want to and do **git init**
4. do **git add .** to add all files from there.
5. **git commit -m "commit notes"
6. **git push https://github.com/StefanSilver3/test_repo.git**
6.1. You can also do **git push origin master** or **git push origin main** (depending on how your branch is named).


### Create a new branch

***Creates a new branch called "your_branch"
Switches to that new branch immediately
You're now working on the new branch instead of your previous branch***

```
git checkout -b your_branch
```
***Pushes your new branch to the remote repository (origin)
Creates the branch on the remote if it doesn't exist
Sets up tracking (-u flag) so future git push and git pull commands know where to go***
```
git push -u origin your_branch
```

**To show branches**
```
git branch
```
