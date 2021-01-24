# VERSION CONTROL

- **Repository** -> Folder under  version control
- **Commit** -> unit of work
- **Clone** -> a copy of the work
- **Trunk** -> Main line of work
- **Branch** -> Separate line of work, thought, or experimentation
- **Marge**-> Process of get a branch back to the truck
- **Tag** -> Mark a particular spot in the work

**GIT** has an architecture of three-trees: *repository* tree, *stage* tree, and the *working*  tree.

`add` command moves files from *working* tree to *stage* tree.

`commit` command moves file from *stage* area to the *repository*.

# GIT Commands
- SHOW GIT CONFIG INFO <br/>
`> git config --list`
- CHECK USER NAME <br/>
`> git config user.name`
- CHANGE USENAME <br/>
`> git config --global user.name "Jaime Bohorquez-Ballen"`
- CHECK USER EMAIL <br/>
`> git config user.email`
- CHANGE USER EMAIL <br/>
`git config --global user.email [your email address here]`
- GITHUB CONFIG FILE <br/>
`~/.gitconfig`
- CLONE EXISTING REPOSITORY ON GITHUB:<br/>
`> git clone URL`
- CREATE A LOCAL REPO <br/>
`> git init`
- STATUS REPO: <br/>
`> git status`
- VIEW CHANGES: <br/>
`> git diff`
- VIEW CHANGES IN STAGE AREA: <br/>
`> git diff --staged`
OR
`> git diff --cached`
- ADD CHANGES TO FILE <br/>
`> git add file_name`
- ADD EVERYTHING <br/>
`> git add .`
- REMOVE FILE:<br\>
`git rm file_name`
- RENAME FILE:<br/>
`git mv old_name new_name`
- COMMIT <br/>
`> git commit -m 'description'`
- COMMIT WITH NO ADDING: <br/>
`git commit -a` OR
`git commit --all`
-COMMIT ALL WITH MESSAGE:<br/>
`git commit -am 'Mesagge'`
- SEND CHANGES TO GITHUB REPOSITORY <br/>
`> git push `

# Commit Message- Best Practices
- Short line summary
- Can be followed by a blank line and a more complete description
- lines with less than 72 characters long
- Present tense
# Commit Log
- View commit log <br/>
`> git log`
- Specific string on log <br/>
`> git log --grep='regular_expresion'`
