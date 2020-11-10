Git status
Git add filename/ git add .
Git reset filenamewithPath
Git commit -m “mesaage”
Git push origin “branchname”
Git stash
Git pull origin “branch”

git reset --hard 590f2505ea8dabd691d01680b45dee104946100a
git push -f -u origin ganapati-dev

git clone --branch dbranch

git remote -v
git remote add upstream remoteurl
git remote -v
git fetch upstream
git checkout branch
git merge upstream/branch
git add -A
git commit -m "Sync 2.2.1-201910122"
git push



merge :
git branch 

git checkout -b newbranch

gity commit 

git checkout master

git merge newbranch









local force fetch 
First, run a fetch to update all origin/<branch> refs to latest:

git fetch --all
Backup your current branch:

git checkout -b backup-master
Then, you have two options:

git reset --hard origin/master
OR If you are on some other branch:

git reset --hard origin/<branch_name>




to delete a;ll untracked files
Sometimes just clean -f does not help. In case you have untracked DIRECTORIES, -d option also needed:

# WARNING: this can't be undone!

git reset --hard HEAD
git clean -f -d
git pull