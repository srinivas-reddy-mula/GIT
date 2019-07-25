#### git 

1. __Git__ is used to Source code management
2. Git is opensource
3. it is a __distributed__ repository management
    * distributed means it will have two repositories
        * Local repository
            * Developers will write  code push the code into __Central repository
        * Central repository
            * Developers will push the code into __repository__
4. Here we are working on branches.
5. if any bugs detected in latest commit we can __ROLL_BACK__ to previous commit 
6. Git will maintain all versions of commits, so we can rollback easily
7. Git will maintain all the __details__ about commit like __developer name__ and __EMAIL__ __TIME__ __DATE__ in __LOGS__
8. Git has __Three__ phases
    * __WORKSPACE__
    * __STAGING / INDEXING AREA__
    * __LOCAL REPOSITORY__
    ![preview](./images/git_phases.png)


##  Git Commands 
1. To initialise a git repository
    *   git init

2. to set usename and email
    *   git config --global user.name <user name>
    *   git config --global user.email "some@gmail.com"

3. To see the all configuration files 
    *   git config --list


4. To __Track__ the files whether Tracked or UnTracked
    *   git status


5. To add workspace or UnTracked files into __Staging/Index__ area
    * to add all untarcked files to Index area
      git add .  

    * if you want to add particular file
          git add <file>


6. To move staged changes to __*Local repository*__

      git commit -m "commit message"

7. To check Logs or Commits

      git log
    git log will display commit ids(SHA format) with modified or commit  date

8. To push __*Local repository*__ code to __*Central Repository*__

      git push 

