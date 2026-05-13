## Step 1:
Create a repo on GitHub.

## Step 2:


## Step 2:
Run code:
```
git clone https://<your_GitHub_repo_link> #Create a folder with the same name and clone the cloud repo into it
```

## Step 3:
Make sure you are in the current folder
Run code:
```
pws #show your current folder
```

and check status
Run code:
```
git status # It should show "on branch main. No commits yet"
git remote -v # check if the git has established connection with GitHub repo. Normally it will show things like this: origin https://<your_GitHub_repo_link> (fetch/push)
```

## Step 4:
Run code:
```
git add . #tell git to track changes in current folder.
```

## Step 5:
Run code:
```
git commit -m "initial commit" #Do a first commit
```

## Step 6:
Run code:
```
git push #push to GitHub. or you can use `git push -u origin main` if you had used 'git init' before.
```

After push, your GitHub repo will change face. Refresh page to check.

## Step 7:
The workflow loop is 
```
Stage -- Commit -- Push
git add . -- git commit -m "" -- git push
```

## Step 8:
Now you can create a new branch with:
```
git switch -c <New_branch_name> #-c means create
```
