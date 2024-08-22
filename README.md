# Basic Git and GitHub Workflow

## Task 1: Repository Setup

1. **GitHub Repository Creation:**
   - Logged into GitHub.
   - Created a new repository named `PLPBasicGitAssignment`.
   - Initialized the repository with a README file.

## Task 2: Local Setup

2. **Local Folder Setup:**
   - Created a new folder on my local machine named `PLPBasicGitAssignment`.
   - Opened a terminal and navigated to the folder:
     ```bash
     cd ~/Documents/PLPBasicGitAssignment
     ```

3. **Git Initialization:**
   - Initialized a new Git repository in the local folder:
     ```bash
     git init
     ```

4. **Connecting to GitHub:**
   - Linked the local repository to the GitHub repository:
     ```bash
     git remote add origin https://github.com/codejoygirl/PLPBasicGitAssignment.git
     ```

## Task 3: Making Changes

5. **Creating a File:**
   - Created a new text file named `hello.txt` with the content `Hello, Git!`.

6. **Committing Changes:**
   - Staged the changes:
     ```bash
     git add hello.txt
     ```
   - Committed the changes:
     ```bash
     git commit -m "Add hello.txt with a greeting"
     ```

## Task 4: Pushing to GitHub

7. **Pushing to GitHub:**
   - Created and switched to the `main` branch:
     ```bash
     git checkout -b main
     ```
   - Pushed the committed changes to the GitHub repository:
     ```bash
     git push -u origin main
     ```

## Task 5: Verification

8. **Verification on GitHub:**
   - Visited the GitHub repository and confirmed that the `hello.txt` file and commit message were visible.
