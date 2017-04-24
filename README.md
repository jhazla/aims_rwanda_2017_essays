## aims_rwanda_2017_essays

To establish the repository:
1) `cd` to the folder you are going to use.
2) Download the repository:
`git clone https://github.com/jhazla/aims_rwanda_2017_essays.git`
3) `ls` to see all the folders and `cd` go to the folder with your name.
4) Do not remove the `stub.txt` file.

You should be doing all the work on your essay in the directory with your name. For every file that is needed for compilation (like `.tex` files, `.bib` file or pictures) you need to add it to the repository. For example, for `blah.tex`:
1) `git add blah.tex`
2) `git commit -m "Added blah"`
3) `git push origin master`

BLAH BLAH TROLOLO
The message after `-m` should give a brief summary of what change was made in the repository.

Later, whenever you edit some files and you want to send changes to repository:
1) `git commit -m "Changed this and that"`
2) `git push origin master`

To update your repository with changes done by others:
`git pull`

To cancel changes in a file (not commited yet):
`git checkout <file_name>`
