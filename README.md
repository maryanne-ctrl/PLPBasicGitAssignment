# PLPBasicGitAssignment
Hands-On Assignment: Basic Git And GitHub Workflow

2. Local Folder Setup:
  - Create a new folder on your local machine
   mkdir PLPBasicGitAssignment.

  - Open a terminal or command prompt and navigate to the created folder.
  cd PLPBasicGitAssignment

3. Git Initialization:
  - Initialize a new Git repository in your local folder.
    git init

4. Connecting to GitHub:

  - Link your local repository to the GitHub repository you created in Task 1.
  $ git remote add origin https://github.com/maryanne-ctrl/PLPBasicGitAssignment.g

Task 3: Making Changes

5. Create a File:

  - Inside your local folder, create a new text file (e.g., `hello.txt`).
  vi hello.txt

  - Add a simple text message (e.g., "Hello, Git!").
   I to insert then type the below
   
Hello, Git! My name is Maryanne. I am Learning basic git commands.
esc :wq to write and quit vim.

cat hello.txt to read the content in my vim file.

6. Committing Changes:

  - Stage the changes.

   ```bash

   git add hello.txt

   ```

  - Commit the changes.

   ```bash
 git commit -m "Second_commit_add_hello_with_greeting"


   ```

Task 4: Pushing to GitHub

7. Pushing to GitHub:

  - Push the committed changes to your GitHub repository.

   ```bash

   git push -u origin main 

   The end..