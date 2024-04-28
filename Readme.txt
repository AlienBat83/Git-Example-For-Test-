Hello 

My name is Yousef Samman 
           and i am practicing how to use git for future plan.

# To make the folder that has this file a repository for git 
       we need to use the code  *( git init )*

# To make sure that this step is successfull check if you can 
     find a hidden folder named .git 


# After that you will add the files you want in the repository and 
         commit them in the local repository.

         In this example which is the readme.txt file 


# Now Inorder to connect your local repository to the remote one in 
       github you need to use the link found in github`s repository
        which is in this example this : 
                                       https://github.com/AlienBat83/Git-Example-For-Test-.git
        And you need to use the command 

                  git remote add name_Repo Link  *(The name can be any name )*   

                  Note : You should use the command 
                                    git branch -m main *( To name the branch you are working in main )*

# Now you can push the files in the remote repository by the command 
                       git push linkOrRemote_Name  Branch_name 

# This text was added in the github website 



# This section will be used to solve a merging conflict ( Vs Code )
# This text is used for conflict (Browser)


# The conflict was solved by these Steps 
   1. You make a change in the remote repository and commit it. 
    2. You make another change in the local repository and commit it. 
     3. The conflict : Both changes are not the same. 
      4. You use the commmand git fetch linkOrRemote_Name Branch_name 
       5. You use the command git merge linkOrRemote_Name/Branch_name 
        6. Both changes are now added in the file editor under 2 names *(Current Change (Local) )* *(Incoming Change (Remote) )*
         7. Choose the changes you want.
          8. Add the file and commit it. 