First I created a new repository in github Then i created a new folder in my local system. Inside my folder I opened git bash where i executed these commands

git init

git remote add origin https://github.com/Manishimha/assignment.git

notepad sample.txt (here I added these contents to the file) hello this is devops assignment

git add .

git commit -m "first commit"

git push origin master

git branch feature-branch

git checkout feature-branch

notepad sample.txt (here I added these contents to the file) I study at Presidency University I am a Btech student

git add .

git commit -m "commit on feature-branch"

git push origin feature-branch

git checkout master

git merge feature-branch

git push origin master
