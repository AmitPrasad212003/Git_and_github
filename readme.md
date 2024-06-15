# Student Demo Repository
The comprehensive list of Git and GitHub commands .

## Git and GitHub Commands

### Setting Up Git

Configure Git with your name and email:
```sh
    git config --global user.name "Your Name"
    git config --global user.email "your.email@example.com"

Basic Git Commands

1.Cloning a Repository: Clone a repository from GitHub to your local machine:

    git clone https://github.com/AmitPrasad212003/Student_demo.git

2.Checking Repository Status: Check the status of your repository:

    git status

3.Adding Changes: Stage changes for commit:

    git add <file>   # To add a specific file
    git add .        # To add all changes

4.Committing Changes: Commit your changes with a message:

    git commit -m "Describe your changes"

5.Pushing Changes: Push your committed changes to the remote repository:

    git push origin main

6.Pulling Changes: Update your local repository with the latest changes from the remote repository:

    git pull origin main

.Branching and Merging

1.Creating a Branch: Create a new branch:

    git checkout -b new-branch

2.Switching Branches: Switch to an existing branch:

    git checkout branch-name

3.Merging Branches: Merge a branch into your current branch:

    git merge branch-name

.Handling Merge Conflicts

* If there are conflicts during merging, Git will notify you. Resolve the conflicts, then:

    git add <file_with_conflicts>
    git commit -m "Resolved merge conflicts"

.Advanced Git Commands

1.Stashing Changes: Temporarily stash your changes:

    git stash

2.Applying Stashed Changes: Apply stashed changes:

    git stash apply

3.Rebasing Branches: Rebase your current branch onto another branch:

    git rebase branch-name

4.Resetting Commits: Reset your branch to a previous commit:

    git reset --hard commit-hash

.Collaborating on GitHub

1.Forking a Repository: Fork a repository to your GitHub account:
    * Go to the repository page on GitHub and click the "Fork"  button.

2.Creating Pull Requests: Create a pull request:

    1.Push your changes to a branch in your forked repository.
    2.Go to the original repository on GitHub.
    3.Click the "New pull request" button.
    4.Select the branch with your changes and follow the prompts to create the pull request.
