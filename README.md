# PLPBasicGitAssignment

# PLP Basic Git Assignment

This repository was created as part of a Git assignment. Below are the steps taken to complete the assignment along with brief explanations.

## Task 1: Repository Setup

### 1. GitHub Repository Creation

- Logged into GitHub and created a new repository named `PLPBasicGitAssignment`.
- Initialized the repository with a `README.md` file to ensure it had an initial commit.

### 2. Local Folder Setup

- Created a new folder named `PLPBasicGitAssignment` on the local machine's Desktop.
- Used Git Bash to navigate to the newly created folder:
  ```bash
  cd C:/Users/Casper/Desktop/PLPBasicGitAssignment
  ```

### 3. Git Initialization

Initialized a new Git repository in the local folder:
bash
Copy code
git init

### 4. Connecting to GitHub -->

Linked the local repository to the GitHub repository created in Task 1:
bash
Copy code
git remote add origin https://github.com/CasperDkk/PLPBasicGitAssignment.git
Task 3: Making Changes

### 5. Create a File

Created a new text file named hello.txt in the local folder.
Added a simple text message (e.g., "Hello, Git!") to the file.

### 6. Committing Changes

Staged the changes:
bash
Copy code
git add hello.txt
Committed the changes:
bash
Copy code
git commit -m "Add hello.txt with a greeting"
Task 4: Pushing to GitHub

### 7. Pushing to GitHub

Pushed the committed changes to the GitHub repository:
bash
Copy code
git push -u origin main
Task 5: Verification

### 8. Verify on GitHub

Visited the GitHub repository in a web browser and confirmed that the hello.txt file and commit message were visible.
