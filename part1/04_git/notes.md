### Git

-  Git is a distributed version control system.
- it tracks changes in the source code.

- **distributed** -> availabilty of copy of code.
- **version control** -> its tracks changes in the source code.
- **github** -> its a cloud based hosting service.
---
#### git initialization
```
git init
```

#### git lifecycle / workflow
```
working dir , git - tracking locally
    |
    |
    |
staging area
    |
    |
    |
github,git repo
```
#### .gitignore
- git will ignore few files, those files will not be pushed
#### stage changes
```
git add .
```
#### commit changes
```
git commit. -m  "<your-message>"
```
#### push
```
git branch -M main
git remote add origin
git remote -v. // verify
git push -u origin main (-u flag means upstream , in future just be gitpush)
```
#### status 
```
git status
```

### Branch

needed when
- working on any new feature or fixes
- working with team members - **parallel development**

#### see branches
```
git branch
```

#### make a local branch / create a branch
```
git switch -c <branch name>
```
#### git switch branch 
```
git switch
```
#### delete branch
```
git branch -d <branch name>
```
#### merge
```
git switch main
git merge dev
git push
```

### updated code
```
git pull
```

