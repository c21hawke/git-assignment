
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
    
    ![Image](https://github.com/c21hawke/git-assignment/blob/main/images/01.png)

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
    
    ![Image](https://github.com/c21hawke/git-assignment/blob/main/images/02.png)
  
    ![Image](https://github.com/c21hawke/git-assignment/blob/main/images/03.png)

## 3. Git initialization command

  ```bash
  git init
  ```
  - ## Screenshot
    
    ![Image](https://github.com/c21hawke/git-assignment/blob/main/images/04.png)

## 4. gitignore file to ignore files when adding files to github

  ```bash
  vi .gitignore
  ```
  - ## Screenshot
    
    ![Image](https://github.com/c21hawke/git-assignment/blob/main/images/05.png)
    
    ![Image](https://github.com/c21hawke/git-assignment/blob/main/images/06.png)

## 5. Git status command

  ```bash
  git status
  ```
  - ## Screenshot
  
    ![Image](https://github.com/c21hawke/git-assignment/blob/main/images/07.png)

## 6. Command to create files

  ```bash
  touch file1.py file2.py
  ```
  - ## Screenshot
    
    ![Image](https://github.com/c21hawke/git-assignment/blob/main/images/08.png)
    
    ![Image](https://github.com/c21hawke/git-assignment/blob/main/images/09.png)

## 7. Git command to add single file to stage
  
  ```bash
  git add file1.py
  ```
  - ## Screenshot
    
    ![Image](https://github.com/c21hawke/git-assignment/blob/main/images/10.png)

## 8. Git command to add all files to stage

  ```bash
  git add .
  ```
  - ## Screenshot
      ![Imagen](https://github.com/c21hawke/git-assignment/blob/main/images/11.png)

## 9. Git command to commit satged files

  ```bash
  git commit -m "first commit after creating files"
  ```
  - ## Screenshot
      ![Image](https://github.com/c21hawke/git-assignment/blob/main/images/12.png)
    
      ![Image](https://github.com/c21hawke/git-assignment/blob/main/images/13.png)

## 10. Git command to log commits
  
  ```bash
  git log
  ```
  - ## Screenshot
    ![Image](https://github.com/c21hawke/git-assignment/blob/main/images/14.png)

  ```bash
  touch fil3.py
  ```
  - ## Screenshot
    ![Image](https://github.com/c21hawke/git-assignment/blob/main/images/15.png)

  ```bash
  git status
  ```
  - ## Screenshot
    ![Image](https://github.com/c21hawke/git-assignment/blob/main/images/16.png)

  ```bash
  git add .
  ```
  - ## Screenshot
    ![Image](https://github.com/c21hawke/git-assignment/blob/main/images/17.png)

  ```bash
  git commit -m "file3 added"
  ```
  - ## Screenshot
    ![Image](https://github.com/c21hawke/git-assignment/blob/main/images/18.png)

  ```bash
  git log
  ```
  - ## Screenshot
    ![Image](https://github.com/c21hawke/git-assignment/blob/main/images/19.png)

  ```bash
  git log --oneline
  ```
  - ## Screenshot
    ![Image](https://github.com/c21hawke/git-assignment/blob/main/images/20.png)

## 11. Git command to list branches

  ```bash
  git branch
  ```
  - ## Screenshot
    ![Image](https://github.com/c21hawke/git-assignment/blob/main/images/21.png)
    
## 12. Git command to create a new branch and switch to that branch

  ```bash
  git branch -c dev
  ```
  ```bash
  git checkout dev
  ```
  - ## Screenshot
    ![Image](https://github.com/c21hawke/git-assignment/blob/main/images/22.png)
   
  ```bash
  git branch
  ```
  - ## Screenshot
    ![Image](https://github.com/c21hawke/git-assignment/blob/main/images/23.png)

## 13. Git command to create a branch and switch to that at the time of creation

  ```bash
  git checkout -b bugtest
  ```
  - ## Screenshot
    ![Image](https://github.com/c21hawke/git-assignment/blob/main/images/24.png)
   
  ```bash
  git branch
  ```
  - ## Screenshot
     ![Image](https://github.com/c21hawke/git-assignment/blob/main/images/25.png) 


## 14. Git command to delete a branch
  
  ```bash
  git branch -d bugtest
  ```
  - ## Screenshot
    ![Image](https://github.com/c21hawke/git-assignment/blob/main/images/26.png) 
   
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
     ![Image](https://github.com/c21hawke/git-assignment/blob/main/images/27.png) 

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
    ![Image](https://github.com/c21hawke/git-assignment/blob/main/images/28.png) 
   
  ```bash
  git status
  ```
  - ## Screenshot
    ![Image](https://github.com/c21hawke/git-assignment/blob/main/images/29.png) 

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
     ![Image](https://github.com/c21hawke/git-assignment/blob/main/images/30.png) 
   
  ```bash
  git checkout dev
  ```
  
  ```bash
  ls
  ```
  
  - ## Screenshot
     ![Image](https://github.com/c21hawke/git-assignment/blob/main/images/31.png) 
   
   
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
    ![Image](https://github.com/c21hawke/git-assignment/blob/main/images/32.png) 
   
 
## 18. Git command to delete a tag
  
  ```bash
  git tag V0.2
  ```
  
  ```bash
  git log --oneline
  ```
  
  - ## Screenshot
    ![Image](https://github.com/c21hawke/git-assignment/blob/main/images/36.png) 
  
  ```bash
  git tag -d V0.2
  ```
  - ## Screenshot
    ![Image](https://github.com/c21hawke/git-assignment/blob/main/images/37.png) 
   

## 19. Git command to clone a github repository
  
  - Go to [link](https://github.com/c21hawke/test-repository.git) and copy a url as shown below
  
    - ## Screenshot
        ![Image](https://github.com/c21hawke/git-assignment/blob/main/images/39.png) 
      
  ```bash
  git clone https://github.com/c21hawke/test-repository.git
  ```
  - ## Screenshot
    ![Image](https://github.com/c21hawke/git-assignment/blob/main/images/40.png) 
  
## 20. Git command to reset the staged files

  ```bash
  git reset
  ````
  
  - ## Screenshot
    ![Image](https://github.com/c21hawke/git-assignment/blob/main/images/41.png) 
    
    
# git-assignment-task2-3
- In this i explained about how to create a open source project with two collaborators

# NOTE : 
   - **RED** color box in annotation indicates - owner 
   - **BLUE** color box in annotation indicates - collaborator

## Authors

- [@c21hawke](https://www.github.com/c21hawke)


## STEP 01:
  - Create a repo with public access under MIT licence
  - Go to settings and then go to collaborators and then click on add people
  
  - ## Screenshot
    
    ![Image](https://github.com/c21hawke/git-assignment-task2-3/blob/main/images/01.png)
   
## STEP 02:
  - Search with username or email id
  
  - ## Screenshot
    
    ![Image](https://github.com/c21hawke/git-assignment-task2-3/blob/main/images/02.png)

## STEP 03:
  - After sending a request you will see username with pending invite
  
  - ## Screenshot
    
    ![Image](https://github.com/c21hawke/git-assignment-task2-3/blob/main/images/03.png)

## STEP 04:
  - The person you had added get an email and also a notification in his/her github account
  
  - ## Screenshot
    
    ![Image](https://github.com/c21hawke/git-assignment-task2-3/blob/main/images/04.png)
 
 ## STEP 05:
  - And then he/she accept invitation in order to collaborate to that project
  
  - ## Screenshot
    
    ![Image](https://github.com/c21hawke/git-assignment-task2-3/blob/main/images/05.png)
## STEP 06:
  - Now go to your account there we see pending invite id gone
  
  - ## Screenshot
    
    ![Image](https://github.com/c21hawke/git-assignment-task2-3/blob/main/images/06.png)
 
## STEP 07:
  - Now create a file in your account and other person also see that file in his github when he pull the repro
  - ## Screenshot
    
    ![Image](https://github.com/c21hawke/git-assignment-task2-3/blob/main/images/07.png)
 
## STEP 08:
  - Ask other person to create a file and raise a pull request with other branch name
  
  - ## Screenshot
    
    ![Image](https://github.com/c21hawke/git-assignment-task2-3/blob/main/images/08.png)
 
## STEP 09:
  - Now we get a pull request and merge that branch with base branch 
  
  - ## Screenshot
    
    ![Image](https://github.com/c21hawke/git-assignment-task2-3/blob/main/images/09.png)
   




   
   

## License

[MIT](https://choosealicense.com/licenses/mit/)


## 🔗 Links
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/c21hawke)

