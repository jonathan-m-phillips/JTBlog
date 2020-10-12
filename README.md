# JTBlog
### Follow these instructions:


1. Clone `git@github.com:boudreaux-phillips-collabo/JTBlog.git`
2. Create a new personal repo with the same project name

#### From terminal in the cloned project IDE:
1. `git remote remove origin`
2. `git remote set-url --add --push origin git@github.com:{your_project}/JTBlog.git`
3. `git remote set-url --add --push origin git@github.com:boudreaux-phillips-collabo/JTBlog.git`
4. `git remote -v`
5. verify you have one fetch to your project repo and one push each to your project repo and the "boudreaux-phillips-collabo"

#### Ensure all branches have been pulled:
1. `git branch -r`
2. `git branch`
3. Compare remote branches to local branches. Pull as needed.

#### Pushing, Pulling and Committing 

* Checkout a branch to work on. 
* Once work is complete, commit and push changes on that branch.
* After pushing, checkout build branch and enter `git merge branch_name_of_branch_being_merged_in`
* Run project in the build branch to test function.
* DO NOT make changes in build branch. Check out corresponding branch for changes and repeat process.
* Once work is complete for the day, check with other actively working members prior to merging the build branch into the master branch.
* Immediately report merge conflicts