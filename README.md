## Example of Working with Remotes

Use Case: Tou have a repository on your computer containing some code. How do you copy this repository to Github? 

0. Create an empty repository on Github for your code.
    - copy the URL that Github shows you.
    
1. Add a remote to your local repository
   ```
   git remote add origin https://github.com/touchtool/example.git
   ```

2. Push some work **and** tell git to use this as the "default" **upstream** repository:
   ``` 
   git push -u origin master
   ```
   
3. Next time (git know your default upstream) just type:
   ```
   git push
   ```
   
 ## Remote Tracking Branches
 
 A remote tracking branch is a branch in **your local repository** that **tracks** a branch on a remote repository
 The notation is: remote_name/branch_name such as origin/master.
 
 ## Git Branches

-todo: write about git branches
