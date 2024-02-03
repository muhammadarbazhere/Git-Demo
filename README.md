In visual studio code, Open the new terminal then
       
       git --version       (to check the version of git)               

#HOW TO CLONE A RESPOSITORY ON OUR LOCAL MACHINE?                 <br/>                 

     git clone <-link of respository we wanted to clone->                             
     git status              (to check to status of respository weather the git is initialized or not)                  
     git add index.html      (to add a change in git)                                     
     git add .               (to add all changes in git)                                       
     git commit -m "your comment here"       (to commit changes in git)                                 
     git branch              (to check the branch   like main or master etc)                    
                        (if git branch name is *master   we can change it by)                   
     git branch -M main      (to rename the branch from master to main)                              
     git push origin main    (main or other branch name in which you want to push code)               

<br/>
#HOW TO ADD A NEW RESPOSITORY?                                                  <br/>

  make a new respository on github  like  arbaz-new                       <br/>
  now make a folder of any name on your local machine then                              <br/>

     git status (as we make new folder so we will initialize git first by git init)
     git init  (to initialize git in the folder)                               
     git remote add origin <-link of arbaz-new respository->     (to attach this folder to repo we made on github.com/...)
 then same as above in cloning 


#HOW TO MAKE MULTILE BRANCHES?                                      

    git branch          (to check the branch name)
    git branch -M main  (to rename the branch name)

    git checkout <branch name>           (to navigate from one branch to another branch)
    git checkout -b <new branch name>    (to create new branch)

    git branch -d <branch name>    (to delete a specific branch)         

<br/>

#Undoing Changes       <br/>

Case 1: staged changes                                                                      
                  git reset <-file name->  (to reSet changes in a specific file)   <br/>
                  git reset               (to reSet changes in all files)              <br/> <br/>

Case 2: commited changes (not reset whole changes JUST get back to last commit)           <br/>
                  git reset HEAD~1                             <br/>

Case 3: commited changes  (get back to any or many commits)                   <br/>
                  git reset <-commit hash->              (we can get all commit hashes or history of commit by   git log   )    <br/>
                  git reset --hard<-commit hash->       (it will not just remove commit from github but also from vs code)          <br/>


<br/>
#WHAT ARE FORKS?

If we want to to add a repo which is on another person's account  <br/>
then we can fork that repo
by forking that repo,                 <br/>
it will be added directly on our github account.
