# **GIT TUTORIAL**

## **Getting Started**

### Clone repository

Clone from remote repository
````sh
git clone https://github.com/R-Daniel/Git-Practice.git
````

### Add to local repository

Start repository
````sh
git init
````

Add remote repository
````sh
git remote add origin https://github.com/R-Daniel/Git-Practice.git
````

## **Local Use**

### Managing changes

Add file to **Stage**
````sh
git add [file-path]
````

Commit changes
````sh
git commit -m "[message]"
````

### Managing Commits

Undo last Commit
````sh
git reset HEAD~1
````

### Interact with remote

Push to remote
````sh
git push
````

Pull from remote
````sh
git pull
````