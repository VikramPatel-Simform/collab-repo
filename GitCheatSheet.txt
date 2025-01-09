Here is a comprehensive list of Git and GitHub commands commonly used by developers every day, along with their use cases:

### Git Commands

1. **`git init`**  
   - Initializes a new Git repository in your project folder.
   - Usage: `git init`

2. **`git clone <repository_url>`**  
   - Clones an existing remote repository to your local machine.
   - Usage: `git clone https://github.com/user/repository.git`

3. **`git status`**  
   - Displays the status of the current repository, showing staged, unstaged, and untracked files.
   - Usage: `git status`

4. **`git add <file>`**  
   - Stages changes (file) for commit.
   - Usage: `git add filename` or `git add .` to add all changes.

5. **`git commit -m "message"`**  
   - Commits the staged changes with a commit message.
   - Usage: `git commit -m "Added new feature"`

6. **`git log`**  
   - Shows the commit history of the repository.
   - Usage: `git log`

7. **`git diff`**  
   - Shows the difference between the working directory and the index (staged files).
   - Usage: `git diff`

8. **`git branch`**  
   - Lists all branches in the repository and marks the current branch.
   - Usage: `git branch`

9. **`git checkout <branch>`**  
   - Switches to a specified branch.
   - Usage: `git checkout feature-branch`

10. **`git checkout -b <new-branch>`**  
    - Creates a new branch and switches to it.
    - Usage: `git checkout -b new-branch`

11. **`git merge <branch>`**  
    - Merges a specific branch into the current branch.
    - Usage: `git merge feature-branch`

12. **`git pull`**  
    - Fetches changes from the remote repository and merges them into the current branch.
    - Usage: `git pull origin main`

13. **`git push`**  
    - Pushes your local commits to the remote repository.
    - Usage: `git push origin main`

14. **`git remote -v`**  
    - Lists the remotes associated with your repository (URL of the remote).
    - Usage: `git remote -v`

15. **`git fetch`**  
    - Fetches changes from the remote repository but does not merge them.
    - Usage: `git fetch origin`

16. **`git reset <commit>`**  
    - Resets the repository to a specific commit (can be used to undo changes).
    - Usage: `git reset --hard <commit_hash>`

17. **`git rebase <branch>`**  
    - Applies commits from one branch onto another (useful for cleaning history).
    - Usage: `git rebase main`

18. **`git stash`**  
    - Temporarily saves changes that you don’t want to commit yet.
    - Usage: `git stash`

19. **`git stash pop`**  
    - Applies the stashed changes back to your working directory.
    - Usage: `git stash pop`

20. **`git rm <file>`**  
    - Removes a file from both the working directory and the staging area.
    - Usage: `git rm filename`

21. **`git log --oneline`**  
    - Shows the commit history in a single line format.
    - Usage: `git log --oneline`

22. **`git show <commit_hash>`**  
    - Shows details about a specific commit.
    - Usage: `git show <commit_hash>`

### GitHub Specific Commands

1. **`git remote add origin <repository_url>`**  
   - Adds a new remote repository (usually for pushing to GitHub).
   - Usage: `git remote add origin https://github.com/user/repository.git`

2. **`git push -u origin <branch>`**  
   - Pushes a local branch to a remote repository and sets the upstream branch.
   - Usage: `git push -u origin feature-branch`

3. **`git pull origin <branch>`**  
   - Pulls changes from a specific branch on GitHub.
   - Usage: `git pull origin main`

4. **`git fetch origin`**  
   - Fetches updates from the remote repository without modifying your working directory.
   - Usage: `git fetch origin`

5. **`git push origin --delete <branch>`**  
   - Deletes a branch from the remote repository.
   - Usage: `git push origin --delete feature-branch`

6. **`git branch -a`**  
   - Lists all local and remote branches.
   - Usage: `git branch -a`

7. **`git config --global user.name "<name>"`**  
   - Sets the global username for Git commits.
   - Usage: `git config --global user.name "Your Name"`

8. **`git config --global user.email "<email>"`**  
   - Sets the global email address for Git commits.
   - Usage: `git config --global user.email "youremail@example.com"`

9. **`git tag <tag_name>`**  
   - Creates a tag (a point in the commit history).
   - Usage: `git tag v1.0.0`

10. **`git push origin <tag_name>`**  
    - Pushes a specific tag to the remote repository.
    - Usage: `git push origin v1.0.0`

11. **`git pull request` (via GitHub CLI)**  
    - Opens a pull request from your local branch to the remote repository's branch (via GitHub CLI).
    - Usage: `gh pr create --base main --head feature-branch`

12. **`gh repo create` (via GitHub CLI)**  
    - Creates a new GitHub repository from the command line.
    - Usage: `gh repo create`

13. **`gh pr merge` (via GitHub CLI)**  
    - Merges a pull request from GitHub.
    - Usage: `gh pr merge <pr_number>`

### Tips for Using Git and GitHub

- **Regular commits**: Commit your changes frequently to save progress.
- **Pull before pushing**: Always `git pull` before `git push` to avoid conflicts.
- **Branching**: Use separate branches for features, fixes, or experiments.

These commands are the core set that will help you manage code repositories effectively in most projects. You can dive deeper into more specific commands as needed, but this will cover most everyday tasks.