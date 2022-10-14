
# Git Assignments

In this repository Git commands are described with example and explanation.



## Authors

- [@c21hawke](https://www.github.com/c21hawke)

# TASK - 1

## 1. Git Command to check the version of git

  ```bash
  git --version
  ```
  
  - ## Screenshot
    
    ![Git Version](https://github.com/c21hawke/git-assignment/blob/main/images/01.png)

## 2. It is a good idea to introduce yourself to Git with your name and public email address before doing any operation

  ```bash
  git config --global user.email "youremail@gmail.com"
  ```
  - It will display your email id given to git
  
  ```bash
  git config --global user.email
  ```

  ```bash
  git config --global user.name "username"
  ```
  - It will display your username given to git
  ```bash
  git config --global user.name
  ```
  - ## Screenshot
    
    ![Git Version](https://github.com/c21hawke/git-assignment/blob/main/images/02.png)
  
    ![Git Version](https://github.com/c21hawke/git-assignment/blob/main/images/03.png)

## 3. Git initialization command

  ```bash
  git init
  ```
  - ## Screenshot
    
    ![Git Version](https://github.com/c21hawke/git-assignment/blob/main/images/04.png)

## 4. gitignore file to ignore files when adding files to github

  ```bash
  vi .gitignore
  ```
  - ## Screenshot
    
    ![Git Version](https://github.com/c21hawke/git-assignment/blob/main/images/05.png)
    
    ![Git Version](https://github.com/c21hawke/git-assignment/blob/main/images/06.png)

## 5. Git status command

  ```bash
  git status
  ```
  - ## Screenshot
  
    ![Git Version](https://github.com/c21hawke/git-assignment/blob/main/images/07.png)

## 6. Command to create files

  ```bash
  touch file1.py file2.py
  ```
  - ## Screenshot
    
    ![Git Version](https://github.com/c21hawke/git-assignment/blob/main/images/08.png)
    
    ![Git Version](https://github.com/c21hawke/git-assignment/blob/main/images/09.png)

## 7. Git command to add single file to stage
  
  ```bash
  git add file1.py
  ```
  - ## Screenshot
    
    ![Git Version](https://github.com/c21hawke/git-assignment/blob/main/images/10.png)

## 8. Git command to add all files to stage

  ```bash
  git add .
  ```
  - ## Screenshot
      ![Git Version](https://github.com/c21hawke/git-assignment/blob/main/images/11.png)

## 9. Git command to commit satged files

  ```bash
  git commit -m "first commit after creating files"
  ```
  - ## Screenshot
      ![Git Version](https://github.com/c21hawke/git-assignment/blob/main/images/12.png)
    
      ![Git Version](https://github.com/c21hawke/git-assignment/blob/main/images/13.png)

## 10. Git command to log commits
  
  ```bash
  git log
  ```
  - ## Screenshot
    ![Git Version](https://github.com/c21hawke/git-assignment/blob/main/images/14.png)

  ```bash
  touch fil3.py
  ```
  - ## Screenshot
    ![Git Version](https://github.com/c21hawke/git-assignment/blob/main/images/15.png)

  ```bash
  git status
  ```
  - ## Screenshot
    ![Git Version](https://github.com/c21hawke/git-assignment/blob/main/images/16.png)

  ```bash
  git add .
  ```
  - ## Screenshot
    ![Git Version](https://github.com/c21hawke/git-assignment/blob/main/images/17.png)

  ```bash
  git commit -m "file3 added"
  ```
  - ## Screenshot
    ![Git Version](https://github.com/c21hawke/git-assignment/blob/main/images/18.png)

  ```bash
  git log
  ```
  - ## Screenshot
    ![Git Version](https://github.com/c21hawke/git-assignment/blob/main/images/19.png)

  ```bash
  git log --oneline
  ```
  - ## Screenshot
    ![Git Version](https://github.com/c21hawke/git-assignment/blob/main/images/20.png)

## 11. Git command to list branches

  ```bash
  git branch
  ```
  - ## Screenshot
    ![Git Version](https://github.com/c21hawke/git-assignment/blob/main/images/21.png)
    
## 12. Git command to create a new branch and switch to that branch

  ```bash
  git branch -c dev
  ```
  ```bash
  git checkout dev
  ```
  - ## Screenshot
    ![Git Version](https://github.com/c21hawke/git-assignment/blob/main/images/22.png)
   
  ```bash
  git branch
  ```
  - ## Screenshot
    ![Git Version](https://github.com/c21hawke/git-assignment/blob/main/images/23.png)

## 13. Git command to create a branch and switch to that at the time of creation

  ```bash
  git checkout -b bugtest
  ```
  - ## Screenshot
    ![Git Version](https://github.com/c21hawke/git-assignment/blob/main/images/24.png)
   
  ```bash
  git branch
  ```
  - ## Screenshot
     ![Git Version](https://github.com/c21hawke/git-assignment/blob/main/images/25.png) 


## 14. Git command to delete a branch
  
  ```bash
  git branch -d bugtest
  ```
  - ## Screenshot
    ![Git Version](https://github.com/c21hawke/git-assignment/blob/main/images/26.png) 
   
  Inorder to delete a branch we nedd to switch to another branch other than deleting branch
  
  ```bash
  git checkout master
  ```
  
  ```bash
  git branch -d bugtest
  ```
  
  ```bash
  git branch
  ```
  - ## Screenshot
     ![Git Version](https://github.com/c21hawke/git-assignment/blob/main/images/27.png) 

## 15. switch to dev branch and create a file  in dev branch

  ```bash
  git checkout dev
  ```
  
  ```bash
  touch devfile1.py
  ```
  
  ```bash
  git status
  ```
  
  ```bash
  git add .
  ```
  
  ```bash
  git status
  ```
  
  ```bash
  git commit -m "devfile1.py added"
  ```
  
  - ## Screenshot
    ![Git Version](https://github.com/c21hawke/git-assignment/blob/main/images/28.png) 
   
  ```bash
  git status
  ```
  - ## Screenshot
    ![Git Version](https://github.com/c21hawke/git-assignment/blob/main/images/29.png) 

## 16. Git command to merge two branches
  
  ```bash
  git checkout master
  ```
  
  ```bash
  ls
  ```
  
  ```bash
  git merge dev
  ```
  
  ```bash
  ls
  ```
  
  - ## Screenshot
     ![Git Version](https://github.com/c21hawke/git-assignment/blob/main/images/30.png) 
   
  ```bash
  git checkout dev
  ```
  
  ```bash
  ls
  ```
  
  - ## Screenshot
     ![Git Version](https://github.com/c21hawke/git-assignment/blob/main/images/31.png) 
   
   
## 17. Git command to add tags

  ```bash
  git log --oneline
  ```
  
  ```bash
  git tag -a V0.1
  ```
  
  ```bash
  git log --oneline
  ```
  
  - ## Screenshot
    ![Git Version](https://github.com/c21hawke/git-assignment/blob/main/images/32.png) 
   
 
## 18. Git command to delete a tag
  
  ```bash
  git tag V0.2
  ```
  
  ```bash
  git log --oneline
  ```
  
  - ## Screenshot
    ![Git Version](https://github.com/c21hawke/git-assignment/blob/main/images/36.png) 
  
  ```bash
  git tag -d V0.2
  ```
  - ## Screenshot
    ![Git Version](https://github.com/c21hawke/git-assignment/blob/main/images/37.png) 
   

## 19. Git command to clone a github repository
  
  - Go to [link](https://github.com/c21hawke/test-repository.git) and copy a url as shown below
  
    - ## Screenshot
        ![Git Version](https://github.com/c21hawke/git-assignment/blob/main/images/39.png) 
      
  ```bash
  git clone https://github.com/c21hawke/test-repository.git
  ```
  - ## Screenshot
    ![Git Version](https://github.com/c21hawke/git-assignment/blob/main/images/40.png) 
  
## 20. Git command to reset the staged files

  ```bash
  git reset
  ````
  
  - ## Screenshot
    ![Git Version](https://github.com/c21hawke/git-assignment/blob/main/images/41.png) 
   
   

## License

[MIT](https://choosealicense.com/licenses/mit/)


## 🔗 Links
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/c21hawke)

