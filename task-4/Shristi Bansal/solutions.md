**#TASK 3**

Hello
I am Shristi Bansal, currently pursuing B-Tech in Computer Science and Engineering from Banasthali Vidyapith. 
**a. What is meant by the term fork and clone?**
A fork is a copy of a repository. Forking a repository allows you to freely experiment with changes without affecting the original project.When you fork a repository, it�s a clone of the entire repository within GitHub with all of its branches. Typically you do a fork if you want to use the current repository as a base to work on a new project or make changes to show differences between the current repository and the new one in large open source projects.
Clone is a Git command line utility which is used to target an existing repository and create a clone, or copy of the target repository.When you create a new repository on GitHub, it exists as a remote location where your project is stored. You can clone your repository to create a local copy on your computer so that you can sync between both the local and remote locations of the project. Cloning is ideal for instances when you need a way to quickly get your own copy of a repository where you may not be contributing to the original project.

**b. What are branches in Github? **
A branch is simply a pointer to one of the commits in the repository.  Git branch is a feature in git used for separating a feature or part of code from you your master in order not to mess something in your main code like suppose you have a website as a project in git and you want to add a new feature to it so you do it by creating a new branch for it so your main code remain the same as it and once you complete it then you merge it with your master.

**c.What is PR? **
A pull request (PR) is a method of submitting contributions to an open development project. It occurs when a developer asks for changes committed to an external repository to be considered for inclusion in a project�s main repository after the peer review.
The git pull command is used to merge a different repository into your local one. So if someone else has a copy of your git repository, and makes changes to it that they would like you to incorporate, they can ask you to pull the changes from their repository; they're requesting a pull, hence the term- pull request.

**d. Can we delete the master branch if not Why? **
It is possible to delete the master branch by executing the following steps:-
1.On the GitHub page for your forked repository, and click on the �Settings� button.
2.Click on the "Branches" tab on the left hand side. There�s a �Default branch� dropdown list near the top of the screen.
3.From there, select placeholder (where placeholder is the dummy name for your new default branch).
4.Confirm that you want to change your default branch.
5.Use the git command-
git push origin :master
the master branch is deleted.

**e. How can we delete a branch? **
This can be done in 2 ways:-
Github:
1. On GitHub, navigate to the main page of the repository.
2. Above the list of files, click NUMBER branches.
3. Scroll to the branch that you want to delete, then click the delete icon.
Git Bash:
In Git Bash, write the command git branch �d <Branch Name> and the branch will be deleted.

**#TASK 2**

Hello
I am Shristi Bansal, currently pursuing B-Tech in Computer Science and Engineering from Banasthali Vidyapith.
The following is a link to the GitHub Repository I have created: https://github.com/shristibansal/github_series

**a)How git workflow works? **
A Git Workflow is a recipe or recommendation for how to use Git to accomplish work in a consistent and productive manner. Git workflows encourage users to leverage Git effectively and consistently. Git offers a lot of flexibility in how users manage changes. Given Git's focus on flexibility, there is no standardized process on how to interact with Git. When working with a team on a Git managed project, it's important to make sure the team is all in agreement on how the flow of changes will be applied. To ensure the team is on the same page, an agreed upon Git workflow should be developed or selected. There are several publicized Git workflows that may be a good fit for your team. 
There is only one central repository. Each developer clones the repository, works locally on the code(remote repository), makes a commit with changes, and push it to the central repository for other developers to pull and use in their work.
This workflow employs two parallel long-running branches:
Master
Develop

**b)What are the different stages of a git project as commit, add? **
Files in a repository go through three stages before being under version control with git:
Untracked: the file exists, but is not part of git's version control
Staged: the file has been added to git's version control but changes have not been committed
Committed: the change has been committed
Git-status is used to understand what stage the files in a repository are at.

**c)Is it possible to do git commit before git add. If you have made any changes? Explain why? **
The git add and git commit commands compose the fundamental Git workflow. These are the two commands that every Git user needs to understand, regardless of their team's collaboration model. They are the means to record versions of a project into the repository's history.
Developing a project revolves around the basic edit/stage/commit pattern. First, you edit your files in the working directory. When you're ready to save a copy of the current state of the project, you stage changes with git add. After you're happy with the staged snapshot, you commit it to the project history with git commit. The git reset command is used to undo a commit or staged snapshot. Hence, it is not possible to do git commit before git add.

**d)Why is git diff used? **
Git diff is a command-line utility. It's a multiuse Git command. When it is executed, it runs a diff function on Git data sources. These data sources can be files, branches, commits, and more. It is used to show changes between commits, commit, and working tree, etc.
It compares the different versions of data sources. The version control system stands for working with a modified version of files. So, the diff command is a useful tool for working with Git.

**e)Can we leave the commit message as blank? **
Git commit messages are necessary to look back and see the changes made during a particular commit. If everyone will just commit without any message, no one would ever know what changes a developer has done. Moreover, you won't be able to track down these changes once you see the history. Git does not recommend to commit without any commit message does not mean that we cannot commit without a message. It is allowed but not recommended.

**#TASK 1**

Hie
This is Shristi Bansal, currently pursuing Btech CSE 2nd year from Banasthali Vidyapith.

**1. What do you mean by git and GitHub? **
Git is a free, open source distributed version control system tool designed to manage a development project's source code history with efficiency. It is a tool a developer installs locally on their computer. It was created by Linus Torvalds in 2005 to develop Linux Kernel. Git has the functionality, performance, security and flexibility that most teams and individual developers need.
GitHub is a cloud based platform built around the Git tool. It is an online service that stores code pushed to it from computers running the git tool. GitHub is an online service to which developers who use Git can connect and upload or download resources.

**2. Why GitHub is so popular and used in most of the projects? **
GitHub is a Git repository hosting service, which provides a web-based graphical interface. It is so popular and used in most of the projects because of the following reasons:-
a)Open, clear communication
b)Public APIs. These allowed others to build upon their work.
c)The right amount of functionality: repo, issue tracking, wiki, GitHub Pages
d)Developer Oriented
e)Superb technology choice: Git
f) Better than other alternatives

**3. What is a version control system? How Git is a VCS? **
Version Control System (VCS) is a software that helps software developers to work together and maintain a complete history of their work. VCS allows developers to work simultaneously and maintain a history record of every version. It doesn't allow overwriting each other's changes.
There are 3 types of VCS:-
Local Version Control System 
Centralised Version Control System 
Distributed/Decentralised Version Control System 
Git is a Distributed Version Control tool that supports distributed non-linear workflows by providing data assurance for developing quality software.Git gives each developer a local copy of the entire development history, and changes are copied from one such repository to another. These changes are imported as additional development branches, and can be merged in the same way as a locally developed branch.

**4. What are the other platforms similar to GitHub? **
GitLab
BitBucket
SourceForge
Launchpad
Google Cloud Source Repositories
AWS CodeCommit
Phabricator

**5. Why are you interested in learning of Git and GitHub? **
I want to learn Git and GitHub due to my curiosity and it will help me advance my knowledge. Learning Git and GitHub will help boost my potential and ease towards open source development. Hie
This is Shristi Bansal, currently pursuing Btech CSE 2nd year from Banasthali Vidyapith.
 
