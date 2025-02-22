# Git-GitHub
In this, we learn Git & GitHub and how to use them.

### 1. Make an account on GitHub  
### 2. Install Git  
Click on this to download Git: [Click on this](https://git-scm.com/downloads)

    
Here are some basic GitHub (Git) commands and their functions:  

### **Basic Git Commands**  

1. **Configure Git (Set Up)**  
   - `git config --global user.name "Your Name"` → Set your Git username  
   - `git config --global user.email "your-email@example.com"` → Set your Git email  

2. **Initialize a Repository**  
   - `git init` → Initialize a new Git repository in the current directory from cmd  

3. **Clone a Repository**  
   - `git clone <repository-url>` → Copy a repository from GitHub to your local machine  

4. **Check Repository Status**  
   - `git status` → Show the status of changes (staged, unstaged, untracked files)  

5. **Add Changes to Staging Area**  
   - `git add <filename>` → Add a specific file to staging  
   - `git add .` → Add all modified and new files to staging  

6. **Commit Changes**  
   - `git commit -m "Your commit message"` → Save changes with a message  

7. **View Commit History**  
   - `git log` → Show commit history  
   - `git log --oneline` → Show commit history in a single-line format  

8. **Push Changes to GitHub**  
   - `git push origin <branch-name>` → Upload commits to a remote repository  

9. **Pull Changes from GitHub**  
   - `git pull origin <branch-name>` → Fetch and merge changes from GitHub  

10. **Create and Switch Branches**  
    - `git branch <branch-name>` → Create a new branch  
    - `git checkout <branch-name>` → Switch to another branch  
    - `git checkout -b <branch-name>` → Create and switch to a new branch  

11. **Merge Branches**  
    - `git merge <branch-name>` → Merge another branch into the current branch  

12. **Delete a Branch**  
    - `git branch -d <branch-name>` → Delete a local branch  
    - `git push origin --delete <branch-name>` → Delete a remote branch  

13. **Undo Changes**  
    - `git reset --hard <commit-hash>` → Reset to a previous commit (removes changes)  
    - `git revert <commit-hash>` → Undo a specific commit (creates a new commit)  

14. **Check Remote Repositories**  
    - `git remote -v` → Show remote repositories  
    - `git remote add origin <repository-url>` → Add a remote repository  

15. **Stash Changes (Temporary Save)**  
    - `git stash` → Save uncommitted changes for later use  
    - `git stash pop` → Reapply stashed changes  

