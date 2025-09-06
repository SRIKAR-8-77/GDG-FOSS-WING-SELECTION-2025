### Answer the following questions in you own words.

> It's not necessary that you havee to know and answer all the questions. Just answer the ones
> you know and write in your own words.

1. Give the difference between the remotes - upstream and origin - with an example.

You answer:suppose there ia a project of your friend now you make the fork then you will get a repo in your account that u use to clone it in your laptop and u commit and push changes in that repo this repo is known as origin repo the repo of your friend who is the original owner of the project is known as upstream repo  and the fact is the term upstream is only defined when some other person is forking it like if u own the repo i mean u are the complete owner of the repo then for you the repo is origin the person who forks the repo, for him your repo will be upstream and his repo will be origin

2. You have two branches A and B and you have currently made some changes in branch A.
You want to move into branch B but do not want to commit the current changes in branch A.
What will you do?

You answer:

3. You were assigned a work to implement a feature and create a PR to your organization's remote repository.
For this you made a branch (say A) and made some changes and commited them. Now you moved to some other branch 
(say B) to do some other assigned work. But later you realisd that have to complete the task assigned earlier 
first and commited some changes in branch B which are meant for branch A. How will you use git to bring the 
changes from branch B to branch A?

You answer:

3. What is the difference between fetching changes and pulling changes?

Your answer: fetching means you can see the changes that teh other branches want to commit and but the changes will not be applied to the branch but when you do pull you actually do both i mean yon fetch and merge the changes.

4. What does -i flag stand for? What is it's significance in git?

You answer:

5. You are working in an organization that follows very strict guidelines for PRs and commits.
You made three commits in your PR and the maintainer says you were supposed to make a single commit.
What will you do in this case?

You answer: if they are small commits i mean if there is possibility of squashing the three commits changes into one commit i would do that but if the commits are large and needed to be commited separately then i have to commit them separately

6. Explain `git merge` and `git rebase` with example(s).

You answer:when a group of people work on a project they have a main branch when a person in that group wants to make some changes he creates a development branch and commits changes and does a pull request for the main branch then the changes from the devlopment branch should be added to the original main branch then for this there are two methods they are git merge and git rebase, when person does a merge the feature branch remains the same i mean the changes form the feature branch will be added to the main branch but the branches will be stored ass they are ,only the results i mean the finel commitments are merged into the main branch but in the rebase the it follows the principle of linearity i mean it totally merges the development branch into main branch i mean after the rebasing everything goes into the account of main branch there will be no history such that a development branch was created everything of the devlopment barnch will be moved to main branch

7. Write the flow how you create a repository and push changes to it. Also mention the commands used at each step.

You answer: first create a repo in the github and git hub will give you a link for the repo and then you create a folder in your local machine and make your project i mean files and then if you want to add the files in to the repo follow the commands step by step 

git init 

git add .

git commit -m "add yo message for the commit"

git remote add origin https://github.com/your-username/my-first-project.git

git push -u origin main

8. How would you prevent a file or folder from getting tracked by git?

Your answer: gitignore is there for that purpose if i have some files which has some data or api keys which i do not want the gt to track then i have to add the mention in the gitignore file then the git will not be able to track them

9. You did not implement the step you mentioned in question 8 and now you have committed and pushed your database's
secret key to the github. How will you remove the key from your git's commit history to avoid any misuse?

You answer:

---