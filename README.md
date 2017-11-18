# resources
Resource folder contains source code and documentations.
======


This instruction shows you how to make your branch and merge it to a group gitHub.

Phase 1 – Clone the group gitHub:
-	Clone the group GitHub

Phase 2a – Make your branch
-	Before making the development branch, please do 

	$git pull origin master

-	Make your branch with convention of using your ucsd login name.  Ideally, if you make a new feature of your work, you should create a new branch, so you can track the feature on its own branch.  If you don't mind then you can reuse the same branch if you created it before and you can skip this step and go on with your changes on phase 2b.

	$git checkout -b mqh001_branch_name

Phase2b – Add your branch to gitHub
-	When you are ready to add your changes to GitHub, do this

	$git add directory/file

	$git commit –m “Add change for xxx”

	$git push --set-upstream origin mqh001_your_branch
             
    Please note when you are done this step, your branch is up on GitHub but it is on its own branch

Phase 3: Merge your branch to the master branch.   Currently this instruction shows you on GitHub UI which has nice UI for merging.
-   Click on the second option of the tap on the UI "XX branches"
-	Click on "Pull".
-	Check for conflict
-	Merge by doing "Merge Pull Request" then "Confirm Merge"

Finally, check your work on the master branch to ensure it successfully merged.

