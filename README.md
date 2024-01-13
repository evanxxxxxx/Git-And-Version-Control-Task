**Git-and-Version-Control**
# Explain version control 
git status
## Explain difference between git and github
Git and GitHub are two related but distinct tools used in software development. Git is a distributed version control system that allows developers to track changes in their code and collaborate with others. It is installed locally on a system and uses local files to store repositories. On the other hand, GitHub is a web-based hosting service for Git repositories that provides a centralized platform for collaboration, sharing code, and hosting projects. It has a built-in user management system and a graphical user interface. While Git is focused on version control and code sharing, GitHub is focused on centralized source code hosting and collaboration. Together, Git and GitHub provide a powerful set of tools for managing and sharing code in software development projects.

### List three other GitHub alternatives
Here are three alternatives to GitHub:
1. GitLab is a web-based DevSecOps platform that offers features and tools for the entire software development lifecycle. It provides both a cloud-based service and a self-hosted solution
2. Bitbucket: Owned by Atlassian, Bitbucket supports both Git and Mercurial. It offers free private repositories and integrates well with other Atlassian tools like Jira 
3. SourceForge: A platform that has been around for a long time and supports Git, Mercurial, and SVN. It provides a variety of features for project management.

#### Explain the difference between git fetch and git pull.
The main difference between **'git fetch'** and **'git pull'** is that git fetch only retrieves the latest changes from the remote repository to the local repository without merging them into the current branch, while git pull not only retrieves the changes but also merges them into the current branch

##### Explain in simple terms git rebase and the command for it
Git rebase is a process that combines or moves a sequence of commits on top of a new base commit. It is a linear way of merging changes, as opposed to the three-way merge used in Git merge. The command for performing a Git rebase is: **'git rebase <base>'**. Here, <base> is the commit or branch you want to base your changes on. If you want to interactively rebase, you can use the following command: **'git rebase --interactive <base>'**. This opens an editor that lets you enter commands for each commit you want to rebase, giving you the opportunity to alter individual commits in the process, such as removing, splitting, or altering an existing series of commits

##### Explain, in simple terms, git cherry-pick and the command for it 
 Git cherry-pick is a command that allows you to selectively apply a specific commit from one branch to another. It is useful for fixing mistakes, such as when a commit is made to the wrong branch, or for applying changes from a feature branch to the main branch. the command for Git cherry-pick is: **'git cherry-pick <commitSha>'**. Here, <commitSha> is the commit reference you want to cherry-pick. You can find a commit reference by using the **'git log command'**

**References**
[Difference Between Git Fetch and Git Pull. (2023, November 1). GeeksforGeeks.] (https://www.geeksforgeeks.org/)
[The Top 10 GitHub Alternatives. (n.d.).] (https://www.wearedevelopers.com/magazine/top-github-alternatives)
[G. (2021, February 26). What is Git Rebase? [Intermediate Git Tutorial]. YouTube.] (https://www.youtube.com/watch?v=_UZEXUrj-Ds)
[What does cherry-picking a commit with Git mean? (n.d.). Stack Overflow.] (https://stackoverflow.com/questions/9339429/)
