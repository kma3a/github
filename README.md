#**GitHub Challenge**

##**Summary**

In this Challenge you will be working with Git and GitHub. You will be learning about how to clone a repositiory, add to a project and pushing those changes to GitHub.

##**Release 0: Clone Repo**

First, get the URL of the repo that you want to clone and copy it. You can find this on the on the right column with HTTPS clone URL. Then go into your terminal and type ```git clone https://github.com/JackMarx/blue1647_rails_curriculum.git```.

Once this is done it should display something like this:

```
Cloning into 'blue1647_rails_curriculum'...
remote: Counting objects: 94, done.
remote: Total 94 (delta 0), reused 0 (delta 0)
Unpacking objects: 100% (94/94), done.
```

##**Release 1: Make a new branch**

Create a new branch. You can do this by putting in ```git branch branch_name``` then move to that branch using ```git checkout branch_name``` or you can use git ```checkout -b branch_name``` which creates the branch and moves you there for you.

##**Release 2: Add and Commit**

On your new branch, add a markdown file to the introductions file on the repo. In this file you should introduce yourself puting down your name, why you are learning rails? and What you hope to be able to get out of this class?

When you are done with that, add your changes using ```git add .``` and commit ```git commit -m "message goes in quotes"``` (Remember to make useful commit messages).  Once you have done this you can view the message using ```git log```.  You can scroll up and down and checkout out the commits use ```q``` to quit the log.

##**Release 3: Check for changes and Push your branch**

Before you push your branch, switch back to your master branch using ```git checkout master```, then ```git pull`` to make sure that your local copy of master is upto date and if someone had made a change it will update your local copy of master. If there is a change, do ```git rebase branch_name``` to put those changes onto your branch. We do this to ensure that you don't have any merge conflicts with your site.

Now, checkout your branch and push your branch up to GitHub using ```git push origin branch_name``` .  You should see something like:

```
To https://github.com/JackMarx/blue1647_rails_curriculum.git
 * [new branch]      branch_name -> branch_name
```

When your branch has been pushed up to GitHub, go to the repo page and you should see a new green box appear under the title.  Click on it and make a pull request.  You can play around with the features take your time.  Besure to make the pull request.  **Do Not Merge The Pull Request At This Time**

Congrats you have just learned how to make changes to a repo on GitHub!!!

##**Challenge: Git Branching**
If you want to learn more about using Git go through (Learn Git Branching)[http://pcottle.github.io/learnGitBranching/]

