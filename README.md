# The 4 milestones to start tracking a project on GitHub are:
Step 1: Initalize Git for the project folder (this will create a local repository)
git init

Step 2: Define/Confirm the local and remote credentials.
git config --global user.name <github_user_name>
git config --global user.email <github_associated_email>
git config --local user.name <github_user_name>
git config --local user.email <github_associated_email>

Step 3: Add a file to the folder and add this file for change tracking on Git
git add <filename.extension>

Step 4: Check the Status & Commit to changes locally
git status
git commit <FILENAME> -m “brief description of changes when versioning the file to be committed”

Step 5: Publish the changes to a remote/centralize repository (GitHub / AzureDevops for others to see your updats)
