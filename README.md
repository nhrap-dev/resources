# Git Instruction

## Connect file to repository:
1)	Open terminal
2)	```cd C:/file/directory/path```
3)	```git init```
4)	```git remote add origin https://github.com/nhrap-dev/example.git```
## Commit file:
1)	```git add -A```
2)	```git commit -m “update comments here!”```
3)	```git push```
a.	if it’s the first push:
i.	```git push -f --set-upstream origin master```
## Branch management:
### Create branch
1)	```git checkout -b branch_name```
2)	```git push origin branch_name```
### View all branches
* ```git branch -a```
### Check out remote branch
1) ```git fetch --all```
2) ```git checkout branch_name```
### Delete Branch
* locally: ```git branch -d branch_name```\
           ```git branch -D branch_name``` (force delete)
* remote: ```git push origin --delete branch_name```
## Clone repository:
1)	Copy https clone url
>img here 
2)	Open terminal
3)	```cd C:/local/repository/directory```
4)	```git clone https://github.com/nhrap-dev/example.git```

