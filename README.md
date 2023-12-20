# Learning init command

Step 1: Create a folder and run cmd -> git init </br>
Step 2: Check status if any untrackable file you have added </br>
Step 3: Add and commit in your own local pc/laptops run cmd ->
</br> git add . <i>for all files to make status staged</i> </br> run cmd -> git commit -m "added files".</br>
Step 4: Again check for git status. </br>
<h5>Local git and repo is ready now create a global(remote) repo and name origin(or something)</h5>
Step 5: Create a new repo without README.md else we have to clone into local also, or we can make later</br>
Step 6: Run command -> git remote add origin <-- https link of remote repo --></br>
Step 7: Run command -> git remove -v (to verify remote) </br>
Step 8: Run command -> check for branch or want to rename branch</br>
cmd -> git branch    and    git branch -M newmain </br>
Step 9: Final push into origin or remote repo with cmd -> git push origin main </br>
cmd -> <b> git push -u origin main </b> (we can use this cmd to set upstream if we are working on a project for long time) <b> next time run cmd only -> <i> git push </i> </b> 