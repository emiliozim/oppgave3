git branch dev
git checkout dev
git add hiof.js
git status
git commit -m "first update"
git push origin dev
git remote add git.md https://github.com/emiliozim/oppgave3.git
git fetch --all
git checkout master
git merge dev
git add mergeConflict.PNG
git commit -m "last update!"
git push origin master