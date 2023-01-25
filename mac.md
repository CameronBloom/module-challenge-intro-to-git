## Research Questions 

Now that you are all set up, it's time to learn a little more about the tools of the trade. Edit this file and answer the following questions. You are going to need to start familiarizing yourself with the [GitHub docs](https://docs.github.com/en). Docs (short for documentation) are the instructions on how to use a languge or program. A large part of your job as a developer will be learning how to read and work with documentation. Please reference the GitHub docs when answering the questions below. If you cannot find what you are looking for in the docs, you can always start to practice your Google skills!

# 1. What is Git?

Git is a free and open source distributed version control system designed to handle everything from small to very large projects with speed and efficiency.

# 2. What is the difference between Git and GitHub?

Git is a version control system that lets you manage and keep track of your source code history. GitHub is a cloud-based hosting service that lets you manage Git repositories.

# 3. Why do we create a branch? 

From the CLI, we can use `git checkout -b <branch name>` to create and switch to a new branch. From GitHub, we navigate to the main page of the repository and click the "Branches" button.

# 4. What is the purpose of a Pull Request?

Pull requests let you tell others about changes you've pushed to a branch in a repository on GitHub. Once a pull request is opened, you can discuss and review the potential changes with collaborators and add follow-up commits before your changes are merged into the base branch.

# 5. What is the command you can use to switch between branches? For example you are working on FIRSTNAME-LASTNAME branch and you want to switch back to main.

We can use `git checkout <branch name>` to switch between branches. Note, we don't use the `-b` tag, as this would create a new branch.

# 6. Explain the difference between `git fetch`, `git merge` and `git pull`. What does each command do?

Use `git fetch` to retrieve new work done by other people. Fetching from a repository grabs all the new remote-tracking branches and tags without merging those changes into your own branches.

Use `git merge` to combine your local changes with changes made by others. Typically, you'd merge a remote-tracking branch (i.e., a branch fetched from a remote repository) with your local branch.

Use `git pull` as a convenient shortcut for completing both `git fetch` and `git merge` in the same command.

# 7. What is a merge conflict?

Merge conflicts happen when you merge branches that have competing commits, and Git needs your help to decide which changes to incorporate in the final merge.

# 8. How do you resolve a merge conflict?

You can resolve simple merge conflicts that involve competing line changes on GitHub, using the conflict editor.

You can resolve merge conflicts in Git by using the command line and a text editor.