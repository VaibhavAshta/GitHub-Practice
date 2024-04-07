## GitHub-Practice

- [git-the simple guide](https://rogerdudler.github.io/git-guide/)
- [git-challenge](https://learngitbranching.js.org/)

1. **Initialize a new repository:**
   ```
   git init
   ```
   This command initializes a new Git repository in the current directory.

2. **Add files to the staging area:**
   ```
   git add <file>
   ```
   This command adds a specific file to the staging area to be included in the next commit. You can also use `git add .` to add all files in the current directory.

3. **Commit changes:**
   ```
   git commit -m "Commit message"
   ```
   This command commits the changes in the staging area to the Git repository with a descriptive commit message.

4. **Check status:**
   ```
   git status
   ```
   This command shows the current status of the repository, including modified files, files in the staging area, and untracked files.

5. **View commit history:**
   ```
   git log
   ```
   This command displays the commit history of the repository, showing the commit hash, author, date, and commit message for each commit.

6. **Create a new branch:**
   ```
   git branch <branch_name>
   ```
   This command creates a new branch with the specified name. To switch to the new branch, use `git checkout <branch_name>`.

7. **Merge branches:**
   ```
   git merge <branch_name>
   ```
   This command merges the changes from the specified branch into the current branch.

8. **Push changes to a remote repository:**
   ```
   git push <remote_name> <branch_name>
   ```
   This command pushes local commits to a remote repository specified by `<remote_name>` and `<branch_name>`.

9. **Pull changes from a remote repository:**
   ```
   git pull <remote_name> <branch_name>
   ```
   This command fetches changes from a remote repository and merges them into the current branch.

10. **Clone a repository:**
    ```
    git clone <repository_url>
    ```
    This command creates a local copy of a remote repository specified by `<repository_url>`.

These are the basic Git commands that cover initializing a repository, adding and committing changes, working with branches, viewing history, and interacting with remote repositories.
