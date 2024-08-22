# PLPBasicGitAssignment

This repository was created as part of a Git assignment. Below are the detailed steps taken to complete the assignment along with the corresponding commands used.

### 1. GitHub Repository Creation

- Logged into GitHub and created a new repository named `PLPBasicGitAssignment`.
- Initialized the repository with a `README.md` file to ensure it had an initial commit.

### 2. Local Folder Setup

- Created a new folder named `PLPBasicGitAssignment` on the local machine's Desktop.
- Navigated to the newly created folder using Git Bash:
  bash

  cd C:/Users/Username/Desktop/PLPBasicGitAssignment

### 3. Git Initialization

Initialized a new Git repository in the local folder:
bash

git init

### 4. Connecting to GitHub

Linked the local repository to the GitHub repository created in Task 1:
bash

git remote add origin https://github.com/username/PLPBasicGitAssignment.git

### 5. Create a File

Created a new text file named hello.txt in the local folder.
Added a simple text message (e.g., "Hello, Git!") to the file.
bash

echo "Hello, Git!" > hello.txt

### 6. Committing Changes

Staged the changes:
bash

git add hello.txt

Committed the changes:
bash

git commit -m "Add hello.txt with a greeting"

### 7. Pushing to GitHub

Pushed the committed changes to the GitHub repository:
bash

git push -u origin main
