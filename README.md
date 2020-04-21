# new-rust-repo
this repo explain How to register a rustlang project in the remote repository

1. $cargo new NEW_PROJECT
2. $cd NEW_PROJECT
3. create new remote repository (access github)
   - should be the same name 
   - add README.md 
   - **NOT** add .gitignore file. already exists in NEW_PROJECT
4. $git remote add origin https://repo_name.git
5. $git pull origin master
6. $git remote -v (Make sure the remote repo is there)
7. $git add .
8. $git commit -m "message"
9. $git push origin master
