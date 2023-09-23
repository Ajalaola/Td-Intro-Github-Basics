# Td-Intro-Github-Basics

### Task 3 - What Do You Understand By Git?

Git is a distributed version control system commonly used in software development. It allows multiple developers to collaborate on a project, tracking changes, managing versions, and ensuring a history of modifications.

### Task 4 - Define Version Control

Version control is a system used to track and manage changes to files and code over time. It enables collaboration by recording who made changes, what changes were made, and when they occurred.


### Committing a project to a GitHub repository involves a few simple steps:

Committing a project to a GitHub repository involves several steps in the Git version control system. Here's a step-by-step description of the process:

1. Initialize a Git Repository:

If your project is not yet a Git repository, you need to initialize it. Open your terminal or command prompt and navigate to your project directory:

cd /path/to/your/project
git init

2. Stage Changes:

Before committing, you need to stage the changes you want to include in the commit. You can use the following command to stage all changes:
git add .
 
 Alternatively, you can specify individual files or directories by replacing . with the file or directory names
 
 3. Commit Changes:

Once you've staged your changes, you're ready to commit them. Use the git commit command with a descriptive commit message:

git commit -m "Your commit message or description"

4. Create a GitHub Repository:

Go to the GitHub website (https://github.com) and log in to your GitHub account.
  Click the '+' icon in the top right corner and select "New repository."
  Fill in the repository name, description, and other settings.
  Click the "Create repository" button.
 5. Link Your Local Repository to GitHub:

To link your local Git repository to the GitHub repository you just created, use the git remote add command. Replace <repository_url> with the URL of your GitHub repository:

git remote add origin <repository_url>

6. Push Your Commits to GitHub:

Finally, you can push your local commits to the GitHub repository:

      git push -u origin master

If you're working on a different branch, replace "master" with the name of your branch.
7. Authentication (if needed):

If you haven't previously authenticated with GitHub, you may be prompted to enter your GitHub username and password or use an access token, depending on your authentication settings.
8. Verification:

After pushing your commits, visit your GitHub repository on the GitHub website to confirm that your project has been successfully committed and pushed.