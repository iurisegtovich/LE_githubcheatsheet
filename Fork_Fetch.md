$	 git init
Initialized empty Git repository in /home/$user.name$/Desktop/github_atomssite_fetch_160311/.git/
$	 git remote add origin https://github.com/$user.name$/atoms_site
$	 git pull
remote: Counting objects: 147, done.
remote: Total 147 (delta 0), reused 0 (delta 0), pack-reused 147
Receiving objects: 100% (147/147), 1.66 MiB | 526.00 KiB/s, done.
Resolving deltas: 100% (55/55), done.
From https://github.com/$user.name$/atoms_site
 * [new branch]      master     -> origin/master
There is no tracking information for the current branch.
Please specify which branch you want to merge with.
See git-pull(1) for details

    git pull <remote> <branch>

If you wish to set tracking information for this branch you can do so with:

    git branch --set-upstream-to=origin/<branch> master

$	 git pull origin master
From https://github.com/$user.name$/atoms_site
 * branch            master     -> FETCH_HEAD

$	 git remote add upstream https://github.com/atoms-ufrj/atoms_site
$	 git fetch upstream
remote: Counting objects: 20, done.
remote: Total 20 (delta 14), reused 14 (delta 14), pack-reused 6
Unpacking objects: 100% (20/20), done.
From https://github.com/atoms-ufrj/atoms_site
 * [new branch]      master     -> upstream/master
$	 git checkout master
Already on 'master'
$	 git merge upstream/master
Updating e0fd03c..7f7cee3
Fast-forward
 Doxyfile                  |  2 +-
 layout/gradient_table.css | 50 -------------------------------------------
 layout/stylesheet.css     | 51 ++++++++++++++++++++++++++++++++++++++++++++
 pages/people.md           | 76 ++++++++++++++++++++++++++++++++++++------------------------------
 pages/publications.md     |  1 +
 5 files changed, 94 insertions(+), 86 deletions(-)
 delete mode 100644 layout/gradient_table.css

$	 trabalhatrabalhatrabalhatrabalhatrabalhatrabalhatrabalha
$	 git add -A
$	 git commit -m "fiz umas coisas aí"

$	 git push origin master
Username for 'https://github.com': $user.name$      
Password for 'https://$user.name$@github.com': 
Counting objects: 30, done.
Delta compression using up to 4 threads.
Compressing objects: 100% (20/20), done.
Writing objects: 100% (20/20), 2.59 KiB | 0 bytes/s, done.
Total 20 (delta 14), reused 0 (delta 0)
To https://github.com/$user.name$/atoms_site
   e0fd03c..7f7cee3  master -> master
$	 só felicidade
