#For New Project
1. Git Initilization
```
git init
```
2. Add files and folder to git for tracking
```
git add .
```
Note: . is for all files and folder , in place of . we can add file name. 
3. After Completing: save all codes as some version
```
git commit -m "[Your_comment_message]"
eg: git commit -m "project initilized"
```
4. Optional step: changing main branch
Note: default branch is always "master"
```
git branch -M "[your_main_branch_name]"
```
5. Add remote repo link or repository url
```
git remote add origin "[your_repository_url]"
```
6. Push the recent commited code to remote 
```
git push -u origin "[your_current_branch_name]"
```
Later (if one push is already done using -u: upstream)
```
git push
```
7. View the status 
```
git status
```
8. 
```
git remote -v
```
9. List the config
```
git config --list
```
10. project base config
```
git config user.name "user-name"
git config user.email "user-email"
```
11. global config
```
git config --global user.email "user-name"
git config --global user.email "user-email"