gitFlow definitions:                   
Repository: The most basic element of GitHub containing all the files for a project and contains revision history. For example, a repository would be used to create and store a project and it's files such as this project.               
To create a repository, click on the + icon at the top right near your profile and click "New repository." From there you can give it a name and create a new repository.          
                          
Clone: A copy of a repository stored on a computer rather than a server and allows a user to edit files on this local copy without being online. Useful for working on projects when in a location without internet.         
To clone a project, navigate to under the repository name and click "Clone or download" and open Git Bash. Change the current working directory to the location you want to cloned repository to be. From there, type "git clone" and paste the url that would be copied from cloning.        
                       
Fork: A copy of another user's repository on your account that you can freely make changes to without affecting the original repository. For example, other members in a group project would fork their own copies of the main project to edit.     
To fork a project, simply click on "fork" in the top right.      
          
Branch: A parallel version of a repository that is contained within the repository but does not affect the master branch which allows a user to work freely without affecting the live version. Useful for projects that require multiple people to edit the project without directly affecting the master branch.         
To branch, click the branch selector menu and type a unique name for the branch. From there select "create branch"      
          
Commit: An individual change to a file similar to saving a file but more organzied because commits contains info on who did what when. Commits are very important when editing and saving files in a repository.            
To commit, scroll down to the bottom of a project to "Commit change," type a detailed description, and click "Commit changes."     
          
Merge: Takes the changes from one branch in the same repository and applies them to another usually using a pull request. Merges are often used to combine other people's work in a project into a master branch.                
To merge, Open the terminal, change the current working directory to your local project and check the branch you wish to merge to. If there any conflicts, resolve them before merging.        
         
Checkout: Checks out of the repository to the $GITHUB_WORKSPACE so the workflow can access the repository.            
To checkout, click "clone or download" and click "Clone with HTTPS." From there, open Git Bash to change the current working directory to where you want the cloned directory and type Git Clone and paste.        
                
Push: sends committed changes to a remote repository on GitHub. Useful for when a user changes something locally they may want to push them so others can access those changes.         
To push, use the command "git push" to push commits made on your local branch to a remote repository.        
           
Pull: A user fetches in changes and merges them. Useful for updating local copies so other people are up to date with their copies.   
To pull, click on "pull request" and pick the branch you wish to merge and add a title/description.        
       
Remote Add/Remove/Show: The version of something on a server that can be connected to other clones so they can be synced.     
          
Status: part of a status check which is an external process that runs each commit in a repository.        
        
Master Branch: The default branch in a repository. Used as the main branch for projects.
