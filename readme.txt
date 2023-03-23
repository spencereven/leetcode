Git is a distributed version control system
Git is free software distributed under the GPL  
//
Learn git:
1. download git from official webstie
2. git config --global user.name " " user.email " " 
  -when u use --global, it means the entire computer will update this
3. C:/User/.. - where u can create a repository
4. mkdir learngit
5. pwd //find out where u create the repository
6. git init // it means initialized empty git repository
7. Create a read.me.txt file in this file (U can't use the editor windows brings)
8. git commit -m ""//desribe what u have done 
 //u can add plenty of files in one time, and commit only once
9. git status // check the status after u modify the file
10. git diff file.name // u can see what u have changed 
11. git log // u can check the history which u commited the file
12.git reset --hard HEAD^ (last version -- HEAD HEAD^ HEAD^^ HEAD100)
13. git reset --hard versionID //(if u wanna rollback to the version u have deleted)
14. git reflog // 