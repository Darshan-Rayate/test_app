Git is a version control system that tracks changes in your files and allows multiple people to collaborate on projects simultaneously. It helps in managing and coordinating work among programmers.

Copy code
git config --global user.name "Your Name"
git config --global user.email "youremail@example.com"
Initializing a Repository:

To start version controlling your project, you need to initialize a Git repository in your project directory.
bash
Copy code

cd your_project_directory
git init

Basic Workflow:

Adding Files: Add files to the staging area to include them in the next commit.


git add filename

Committing Changes: Save the changes in the staging area to the repository.

Copy code
git commit -m "Commit message"

Viewing Changes: Check the status of your repository and see the changes made.



git status


Branching:
Git allows you to create branches to work on new features or bug fixes without affecting the main codebase.

git branch branch_name
git checkout branch_name
Merging:
After completing work on a branch, you can merge it back into the main branch (usually master or main).

git checkout main
git merge branch_name
Remote Repositories:
Git enables collaboration by allowing you to work with remote repositories hosted on platforms like GitHub, GitLab, or Bitbucket.

git remote add origin <remote_repository_URL>
git push -u origin main
Pulling Changes:
Fetch changes from a remote repository and integrate them into your local repository.

git pull origin main
Cloning Repositories:
You can copy a repository from a remote location to your local machine using the git clone command.

git clone <repository_URL>
Undoing Changes:
Git provides various ways to undo changes, like discarding changes in the working directory, unstaging files, or reverting to a previous commit.

git checkout -- filename
