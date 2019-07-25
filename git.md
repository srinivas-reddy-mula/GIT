  ##              GIT

 #### 1. Git is used to Source code management
 #### 2. Git is opensource
 #### 3. it is a distributed repository management
      distributed means it will have two repositories
          Local repository
              Developers will write  code push the code into Central repository
          Central repository
              Developers will push the code into repository
 #### 4. Here we are working on branches.
 #### 5. if any bugs detected in latest commit we can ROLL_BACK to previous commit 
 #### 6. Git will maintain all versions of commits, so we can rollback easily
 #### 7. Git will maintain all the details about commit like developer name and EMAIL TIME DATE in LOGS
 #### 8. Git has Three phases
      1. WORKSPACE
      2. STAGING / INDEXING AREA
      3. LOCAL REPOSITORY
![preview](./images/git_phases.png)


####      Git Commands 
#### 1. To initialise a git repository
        git init

#### 2. to set usename and email
        git config --global user.name <user name>
        git config --global user.email "some@gmail.com"

#### 3. To see the all configuration files 
        git config --list


#### 4. To Track the files whether Tracked or UnTracked
        git status


 #### 5. To add workspace or UnTracked files into Staging/Index area
      to add all untarcked files to Index area
          git add .  

      if you want to add particular file
          git add <file>


 #### 6. To move staged changes to  Local repository 

      git commit -m "commit message"

 #### 7. To check Logs or Commits

      git log
  git log will display commit    ids(SHA format) with modified   or commit  date

 #### 8. To push  Local repository  code to  Central Repository 

      git push 

 #### 9. To see many logs comfortably
    '''
    git log --oneline
    '''

