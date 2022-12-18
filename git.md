## …or create a new repository on the command line
```bash
echo "# Golang-Study" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/nigdanil/Golang-Study.git
git push -u origin main
```
## …or push an existing repository from the command line
```bash
git remote add origin https://github.com/nigdanil/Golang-Study.git
git branch -M main
git push -u origin main
```
## How push to project
```bash
git status
git add .
git commit -m "Text what you do!"
git push -u origin main
```