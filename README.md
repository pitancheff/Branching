create a new repository on the command line

echo # Branching >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/pitancheff/Branching.git
git push -u origin master


git remote -v -  determine the URL that a local Git repository was originally cloned from
git add -A - Add everything
 

Commit: 

git commit -a -m "Made other change"

Get latest
git fetch origin



Branches:

git checkout -b feature_x - create a new branch named "feature_x" and switch to it using
git branch -a    show all the branches git knows 
git branch -d feature_x delete branch
git push origin <branch> - push the branch
git push origin --delete <branchName> Delete remote branch
git push origin :<branchName> Delete remote brench


Merge:
git merge <branch>  -to merge another branch into your active branch (e.g. master), use
git add <filename> -mark them as merged with
git diff <source_branch> <target_branch> - before merging changes, you can also preview them by using


Credentials:
git config --global credential.helper cache
git log --oneline --decorate --graph --all




Config a merge tool
git config --global merge.tool "meld"
git config --global mergetool.meld.path "C:\Program Files (x86)\Meld\Meld.exe"
