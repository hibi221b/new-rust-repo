# new-rust-repo
this repo explain How to register a rustlang project in the remote repository

1. $cargo new NEW_PROJECT
2. create new remote repository
   - should be same name 
   - add README.md 
   - .gitignore file already exists in NEW_PROJECT
3. $git remote add origin https://repo_name.git
4. $git pull origin master
5. $git remote -v (Make sure the remote repo is there)
6. $git add .
7. $git commit -m "message"
8. $git push origin master
