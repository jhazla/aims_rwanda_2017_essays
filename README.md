# aims_rwanda_2017_essays

### Establishing the repository:
1) `cd` to the folder you are going to use.
2) Download the repository:
`git clone git@github.com:jhazla/aims_rwanda_2017_essays.git`
3) `ls` to see all the folders and `cd` go to the folder with your name.
4) Do not remove the `stub.txt` file.

### Checking status (do it often)
`git status`

### Updating the repository
`git pull`

### Adding a new file
`git add <file_name>`

### Adding all modified files for commit
`git add -u`

### Reverting modified file to the last commit
`git checkout <file_name>`

### Making your changes visible online
`git commit -m "<commit message>"`<br>
`git push origin master` (just `git push` also works most of the time)

### Merging a conflict
`git pull`<br>
`git mergetool`<br>
`git commit -m "<message>"`<br>
`git push`

### Deleting a file
`git rm <file>` (later also commit and push)
