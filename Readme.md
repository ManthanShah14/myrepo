-> V1

git config --global user.name "Manthan Shah"
git config --global user.email manthanshah140206@email.com
git config --global --list
git init
ls
ls -force
git status
git add <file>   <!-- git add index.html -->
git status
git commit -m "First v1 of index.html"
git branch
git log


-> V2 (to change in the file which is alredy commited)
git status
git diff
git add index.html
git add Readme.md
git status
git commit -m "This is v2 of index.html"
git log


 git show (id) <!--here the id put here to show old commits -->
 git checkout (id) * or <file>  <!-- If You want old verions of your file-->