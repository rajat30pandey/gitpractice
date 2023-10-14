## Github_QDLC(L4)

**Push, Commit, Add:**

1. What does the "git add" command do in Git?
    Ans- "git add" is used to select specific changes (or entire files) to be included in the next commit.

2. How do you stage changes for a commit in Git?
    Ans- Stage change can be done by using below commands
        git add <filename> (to made change in specific file).
        git add . (to made chnage in current directory).
        to Check Staged Changes
        git  status

3. What is a Git commit, and how is it different from a push?
    Ans- git commit command is used to create a new commit including the staged changes.
        git commit -m "Your commit message
        While Git push is a command used to upload local repository commits to a remote repository, making them accessible to others.
        git push -u origin main

4. How can you create a Git commit with a commit message?
    Ans- git commit -m "Your commit message" 

5. What does "git push" do in Git, and why is it important?
    Ans- git push -u origin main
        command used to upload local repository commits to a remote repository, making them accessible to others.

6. How do you push your local Git commits to a remote repository?
    Ans- git push -u origin main

7. Can you explain the difference between "git add" and "git commit"?
    Ans- Both git add and git commit are essential Git commands used to manage changes in a Git repository.

        'git add' is used to stage changes for the next commit. When you make modifications to files in your working directory, these changes are considered "unstaged" or "untracked" by Git.

        'git commit' creates a new commit, 

**Config:**

8. What is the purpose of Git configuration settings?
    Ans- Git configuration setting is required for Customization and Personalization, Integration with External Tools.

9. How do you set your Git username and email globally?
    Ans- git config --global user.name "Your Name"
        git config --global user.email "your.email@example.com"

10. What is the difference between local and global Git configurations?
    Ans- Local Git configuration applies at the repository level. When you set a configuration locally, it affects only the current repository where the configuration is applied, while Global Git configuration applies at the user level. When you set a configuration globally, it affects all repositories for the current user on that machine.

11. How can you view your Git configuration settings?
    Ans- git config --global user.name
        git config --global user.email

12. Why is it important to configure your Git identity?
    Ans- Git identity configuration is important for version control, collaborative software development, Authorship and Attribution

**Merge, Pull, Branch:**

13. What is a Git branch, and why do we use them?
    Ans- A Git branch is a parallel line of development within a Git repository. It allows you to isolate changes, work on new features, fix bugs, or experiment without affecting the main project or other branches.

14. How do you create a new Git branch?
    Ans- By using git branch <branch_name> syntax.

15. What is the "git merge" command used for in Git?
    Ans- The git merge command in Git is used to integrate changes from one branch into another.

16. How do you merge changes from one branch into another?
    Ans- Below are the steps for branch merging.
        git checkout <target_branch> (Switch to the Target Branch)
        git merge <source_branch> (Initiate the Merge)
        git add .
        git commit (Complete the Merge)
        git push (Finish the Merge Process)

17. What is a merge conflict, and how can you resolve it?
    Ans- Not done

18. What is the purpose of the "git pull" command in Git?
    Ans- The git pull command in Git is used to fetch and merge changes from a remote repository into your local repository. 
        It's a combination of two Git commands: git fetch and git merge.

19. How do you update your local repository with changes from a remote repository using "git pull"?
    Ans. By using below commands.
        git branch
        git pull
        git pull origin main
        git add .
        git commit  
        git status

20. Can you explain the difference between "git merge" and "git pull"?
    Ans- 'git merge' is primarily used to integrate changes from one branch into another within a local repository
        'git pull' It's typically used to update your local repository with changes from a remote repository and incorporate them into your working branch


**General Git:**

21. What is Git, and what problem does it solve in software development?
    Ans- Git is a distributed version control system (DVCS) designed to manage software development projects efficiently.
    It allows multiple developers to work collaboratively on a project, tracking changes, coordinating contributions, and maintaining a complete history of revisions.

22. How do you initialize a Git repository in a directory?
    Ans- By using below commands
        cd /path/to/directory
        git init

23. How do you check the status of your Git repository?
    Ans- By using below commands
        cd /path/to/git/repository
        git status

24. What is the purpose of the ".gitignore" file in Git?
    Ans-  'gitignore' file is a valuable tool for maintaining a clean and organized repository by excluding unnecessary files, 
    improving performance, ensuring security, and promoting collaboration in a version-controlled project.

25. How can you view the commit history of a Git repository?
    Ans- By using below comand.
        git log

26. How do you create a new Git repository on a remote hosting service like GitHub or GitLab?
    Ans- By using below comand.
        'cd /path/to/your/project'
        'git init'
        'git add .'
        'git commit -m "Initial commit'
        'git push -u origin main'

27. What is the purpose of a Git remote?
    Ans- The purpose of a Git remote is to establish a connection between your local Git repository and a copy of that repository hosted elsewhere, 
    typically on a remote server or another location.

28. How can you add a remote repository to your local Git repository?
    Ans- By using below comand.
        git remote add origin https://github.com/username/repo.git

29. What is the Git workflow for making changes, committing, and pushing to a remote repository?
    Ans- Not done

30. How do you undo the last Git commit?
    Ans- Comands are a follows:
        git reset --soft HEAD^
        git reset HEAD^
        git reset --hard HEAD^
        git add <files>
        git commit --amend
        
