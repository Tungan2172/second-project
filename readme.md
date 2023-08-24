# Crete repository  

1. cd project_directory
2. touch file
3. create readme.md file
4. fill readme
5. git add .
6. git status
7. git commit -m "first commit"
8. if tour account doesn`t have a public key then  
generate ssh-key ssh-keygen -t ed25519 -C "message" || ssh-keygen -t rsa -b 4096 -C
9. Connect github with repo by ssh (copy cat ~/.ssh/id_rsa.pub)
10.  Check key - ssh -T git@github.com
11. if you already have key then (copy ssh in repo site) git remote add origin git@github.com:%ИМЯ_АККАУНТА%/first-project.git
12. Check connection between repo and github git remote -v
13. first commit - git push -u origin master
14. Other commits git push
 
git log --oneline // print last log  
your last hash stored in ~/.git file  
git statuses - untracked/staged/modified/tracked

1. after create file his is untracked
2. after git add file gis is staged && tracked(git track his modifies (differ between his and his in repo))
3. after change some data in the file, his have status a modified && tracked
4. in git status your will see 2 snapshots of the file (1- staged, 2 - modified)
5. git add file again. And the file have status staged. In git status you will see only 1 snapshot
6. after git commit. All staged files will be commited on the repo.
7. git push transmit the commit on the remote storage.
