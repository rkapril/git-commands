# git-commands
![image](https://github.com/rkapril/git-commands/assets/61505106/ed08bd6a-27cb-4428-8987-0f20e31c8489)

```
// Create new folder
mkdir Story
```
```
// Change directory
cd Story
```
```
// Create new file
touch chapter1.txt
```
```
// Initialized Git
git init
```
```
// Show all files
ls -a
```
```
// Check status
git status
```
```
// Add to staging area
git add chapter1.txt
git status
```
```
// Commit
git commit -m "Complete Chapter 1"
git log
```
```
// Create new files
touch chapter2.txt
touch chapter3.txt
```
```
// Add to staging area
git add .
git commit -m "Complete Chapter 2 and 3"
git log
```
```
// Rollback
git diff chapter3.txt
git checkout chapter3.txt
```
```
// Create gitignore file
touch .gitignore
```
```
// Remove files from the staging area
git rm --cached -r .
```
