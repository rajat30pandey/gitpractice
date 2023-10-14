# Github_QDLC(L1)

1. What is GitHub?
    Ans.  A platform for developers/ coders to host and review code, manage projects, and collaborate with a community of other developers.

2. How do you create a GitHub account?
    Ans. We can create GitHub profile using GitHub web portal i.e https://github.com

3. What is a repository in GitHub?
    Ans. Repository is a central location where files, code, and other resources related to a project are stored and managed. 

4. How can you create a new repository on GitHub?
    Ans. We can use the below commands in CMD.
        git init
        git add README.md
        git commit -m "practice1"
        git branch -M main
        git remote add origin https://github.com/rajat30pandey/gitpractice
        git push -u origin main

5. What is a README.md file, and why is it important in a GitHub repository?
    Ans. This command stages the README.md file for committing, which means Git will track changes to this file.
    
6. How do you add files to a GitHub repository?
    Ans. we can add files by using beloww commands.
        git add practice.txt
        git commit -m "pratice file added"
        git push -u origin main

7. How can you commit changes to a repository in GitHub?
    Ans. We can commit chnages by using below comand and pushing back to portal.
            git commit -m "pratice file modified"
            git push -u origin main

8. What is a pull request, and how do you create one?
    Ans. GitHub will prompt you to create a pull request to merge the selected branch into the main branch

9. What is a fork in GitHub?
    Ans.To get someone's repository to our directory, we can use fork

10. How do you clone a repository to your local machine?
    Ans. We can clone by using below command.
        git clone https://github.com/rajat30pandey/gitpractice

11. How do you push changes from your local machine to a GitHub repository?
    Ans. We can push chnages by using below comand.
             git commit -m "pratice file modified"
                git push -u origin main

12. What is a branch in GitHub, and why would you use it?
    Ans. A branch is a parallel line of development that allows you to work on a set of changes (additions, modifications, or deletions) to the codebase without affecting the main or default branch.

13. How can you merge a branch into the main/master branch?
    Ans. We can merge branch by using below commands.
        git checkout main
        git fetch origin
        git merge <branch_name>
        git commit  
        git push origin main

14. What is the purpose of the "Issues" tab in a GitHub repository?
    Ans. Issues are used to track todos, bugs, feature requests.

15. How do you close an issue on GitHub?
    Ans. We can use below command in git cli.
        git fetch origin
        git commit -m "Fixing issue #42"
        git commit -m "Closes https://github.com/username/repository/issues/42"
        git push origin branch_name



