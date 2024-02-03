       git --version       (to check the version of git)               

#HOW TO CLONE A RESPOSITORY ON OUR LOCAL MACHINE?                 <br/>                 

     git clone <-link of respository we wanted to clone->                             
     git status              (to check to status of respository)                  
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

     git init  (to initialize git in the folder)                               
     git remote add origin <-link of arbaz-new respository->        (to add code to the repo we made on github.com/...)
 then same as above in cloning 


#HOW TO MAKE MULTILE BRANCHES?                                      

    git branch          (to check the branch name)
    git branch -M main  (to rename the branch name)

    git checkout <branch name>           (to navigate from one branch to another branch)
    git checkout -b <new branch name>    (to create new branch)

    git branch -d <branch name>    (to delete a specific branch)         

<br/>

#WHAT ARE FORKS?

If we want to to add a repo which is on another person's account  <br/>
then we can fork that repo
by forking that repo,                 <br/>
it will be added directly on our github account.
