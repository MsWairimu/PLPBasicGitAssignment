KABUU CHARITY ASSIGNMENT DOCUMENTATION
  
GitHub and Local Repository Setup

  Task 1: Repository Setup

  A. Create a GitHub Repository
1.  Log in to your GitHub account: 
   - Open your web browser and go to [GitHub](https://github.com/).
   - Enter your username and password to log in.

2.  Create a new repository: 
   - Click on the `+` icon at the top right corner of the page and select  New repository .
   - Name your repository `PLPBasicGitAssignment`.
   - Check the box that says  Initialize this repository with a README .
   - Click on the  Create repository  button.

  Task 2: Local Setup

  B. Local Folder Setup

1.  Create a new folder on your local machine: 
   - Navigate to the location on your computer where you want to create the folder.
   - Create a new folder and name it `PLPBasicGitAssignment`.

2.  Open a terminal or command prompt: 
   -  On Windows:  Press `Win + R`, type `cmd`, and hit `Enter`.
   - Use the `cd` command to navigate to the folder you just created:
     bash
     cd path/to/PLPBasicGitAssignment
     

  C. Git Initialization

1.  Initialize a new Git repository: 
   - In your terminal, ensure you are inside the `PLPBasicGitAssignment` folder.
   - Run the following command to initialize a Git repository:
     bash
     git init
     

  D. Connecting to GitHub

1.  Link your local repository to the GitHub repository: 
   - In your terminal, add the remote repository URL. Replace `<repository-url>` with the actual URL of your GitHub repository.
     bash
     git remote add origin https://github.com/<username>/PLPBasicGitAssignment.git
     

  Task 3: Making Changes

  E. Create a File
1.  Create a new text file: 
   - Open a text editor and create a file named `hello.txt`.
   - Add the following text to the file:
     
     Hello, Git!
   - Save the file in your `PLPBasicGitAssignment` folder.

2.  Alternatively, use the command line: 
   -  On Windows: 
     bash
     echo Hello, Git! > hello.txt
   
     

  F. Committing Changes
1.  Stage the changes: 
   - In your terminal, run the following command to add `hello.txt` to the staging area:
     bash
     git add hello.txt
     

2.  Commit the changes: 
   - Commit the changes with a message describing what you did:
     bash
     git commit -m  Add hello.txt with a greeting 
     

  Task 4: Pushing to GitHub

  G. Pushing to GitHub
1.  Push the committed changes: 
   - In your terminal, push the changes to the GitHub repository:
     bash
     git push -u origin main
     git push -u origin main
     

  Task 5: Verification

  8. Verify on GitHub

1.  Visit your GitHub repository: 
   - Open your web browser and navigate to your GitHub repository 
   - Verify that the `hello.txt` file is present and that the commit message  Add hello.txt with a greeting  is visible.


