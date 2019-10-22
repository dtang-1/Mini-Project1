gitFlow definitions:                   
Repository: The most basic element of GitHub containing all the files for a project and contains revision history. For example, a repository would be used to create and store a project and it's files such as this project.               
Clone: A copy of a repository stored on a computer rather than a server and allows a user to edit files on this local copy without being online. Useful for working on projects when in a location without internet.         
Fork: A copy of another user's repository on your account that you can freely make changes to without affecting the original repository. For example, other members in a group project would fork their own copies of the main project to edit.     
Branch: A parallel version of a repository that is contained within the repository but does not affect the master branch which allows a user to work freely without affecting the live version. Useful for projects that require multiple people to edit the project without directly affecting the master branch. Also allows for users to experiement with variations of format.         
Commit: An individual change to a file similar to saving a file but more organzied because commits contains info on who did what when. Commits are very important when editing and saving files in a repository.            
Merge: Takes the changes from one branch in the same repository and applies them to another usually using a pull request. Merges are often used to combine other people's work in a project into a master branch.                
Checkout: Checks out of the repository to the $GITHUB_WORKSPACE so the workflow can access the repository.            
Push: sends committed changes to a remote repository on GitHub. Useful for when a user changes something locally they may want to push them so others can access those changes.         
Pull: A user fetches in changes and merges them. Useful for updating local copies so other people are up to date with their copies.   
Remote Add/Remove/Show: The version of something on a server that can be connected to other clones so they can be synced.     
Status: part of a status check which is an external process that runs each commit in a repository.        
Master Branch: The default branch in a repository. Used as the main branch for projects.
