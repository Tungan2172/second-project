# Crete repository  

1. cd project_directory
2. touch file
3. create readme.md file
4. fill readme
5. git add .
6. git status
7. git commit -m "first commit"
8. generate ssh-key ssh-keygen -t ed25519 -C "message" || ssh-keygen -t rsa -b 4096 -C
9. Connect github with repo by ssh (copy cat ~/.ssh/id_rsa.pub)
10.  Check key - ssh -T git@github.com
11. git remote add origin git@github.com:%ИМЯ_АККАУНТА%/first-project.git
12. Check connection between repo and github git remote -v
13. first commit - git push -u origin master
14. Other commits git push
 
