Demo readme.md --> https://docs.google.com/document/d/1rRjZYHXfp7uD0S1Mx1Ujr0QuNNWlL55x2n_MgfuNZoI/edit

Hey yo
Its A man here hows going 

### Different stages of a file
- untracked : git does not aware of the file
- unmodified : git is aware of the file but there is no changes in file
- modified : there are some changes in the file
- staged : git knows that the change is added to be commited

### cloaning 
- git clone HTTPS_LINK_without_Commas

### status checking
- git status

### adding
- git add file_name_with_extension
- to add all at once -> git add .

### commit 
- git commit -m "comment"

### push 
- git push origin main

***Sometimes we initiate a project in local system then think to create repo on git***
1. for that create project folder on local machine
2. and then run git init in the folder which folder you want to create as a repo
3. then we will create a repo in github and copy its HTTPS link
4. in local folder using -> git remote add origin link
5. to verify linking of local project to new repo -> git remote -v
6. to check the branch -> git branch
7. rename the brank -> git branch -M new_name
8. git push origin main

### Mearging of the branches
1. finding the diff between branches -> git diff branch_name_with_which_we_have_to_compare_currnt_branch
2. 