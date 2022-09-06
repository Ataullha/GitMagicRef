# Basic-GIT-Commands

Basic
---

<hr>

- git init <br>
- git add . <br>
- git commit -m "message" <br>
- git remote add origin [repository_link] <br>
- git pull origin [branch_name] (you may have to provide your username and password(now as personal token [Settings->Developer settings->personal access tokens]) <br>
- git push origin [branch_name]/ git push origin main/ git push origin [branch_name] --force

<hr>

How It Works
---
<pre>


LOCAL 
WORKING DIRECTORY           
                -     (add)     -       
                                stage           
                                    -       (commit)    -          
                                                        LOCAL 
                                                        REPOSITORY                
                                                                 -       (pull)       -       
                                                                                      REMOTE 
                                                                                      REPOSITORY
                                                                                       
</pre>

In Depth
---
                                                                                                                              
                                                                                                                              
  - **git init** <br>
    -  for initialize any local repository
  
  - **git clone https://....** <br>
    -  for cloning any existing or other repository from github to your own local machine
  
  - **git status** <br>
    -  current status for your git local repository
  
  - **git add --all / git add --A** <br>
    -  add every file we create or modify in the git local repository we make
  
  - <b>git add .</b> <br>
    -  add(with .) everything under the current directory of the file we are working or we clone from the remote repository
  
  - **git reset** <br>
    -  reset all progress we stages(Note)/commited at our local repository
  
  - <b>git add *</b> <br>
    -  only add not deleted file to the stage
  
  - <b>git add *.file_extension,</b> <br>
    -  only add not deleted file with the specific file extension to the stage
  
  - **git commit -m "message"** <br>
    -  commit those add to the local git repository
  
  - **git reset HEAD~** <br>
    -  reset after commit but not deleted file
  
  - **git reset --hard** <br>
    -  reset everything to the past stage after commit
 
 - **git rm [a_file (file_name.file_extension)]** <br>
    -  remove the file from the folder and also stage the folder where manual delete don't do that
    - but if we modify any file then it's not possible to remove it using git rm two.txt it won't let us do it untill we commit the modified version then we have to use force remove

- **git rm [a_file] -f** <br>
  -  for force remove

- **git rm --cached t[file_name.file_extension]** <br>
  -  delete it from local git repository storage(stage) but not delete it from the local storage 

- **git rm -r [folder_name]** <br>
  -  recursively delete everything at that folder

- **git branch** <br>
  -  show the branches at the repository
  -  means we are now at that repository

- **git branch [branch_name]** <br>
  -  add a new branch to the local repo

- **git checkout [branch_name]** <br>
  -  for going to another git branch from a branch
  -  the git folder also control the visibility from branch to branch if we are in a branch call 'a' then if there has three files 1,2,3 
     and if we don't merge it and **commit it** then if we switch anotehr branch 'b' where there is no file we can't see those 1,2,3 files before we do        any type of merge from the 'a' branch to the b or main(here we need to create the 'b' branch after merging 'a' to main) ... :)

- **git merge [branch_name]** <br>
  -  for mergeing the branch we are now to the [branch_name] we want

- **git push origin [branch_name]** <br>
  -  for pushing from local to the remote repository

- **git remote add origin [repository_link]** <br>
  -  for link the github repository into local repository

- **git push origin [branch_name] --force** <br>
  -  all previous work will be destroyed **

<hr>

- **push** =  local repository to remote repository <br>
- **fetch** = for fetching but not get those files locally <br>
- **pull** = fetch + merge for pulling that means basically fetching and merging data and make them store and visible in the local repository
