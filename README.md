# Commands (Basics) ->
git init

git add .

git commit -m "Init"

git remote add origin https://github.com/A-R-M-028/Form_react.git

git branch -M main

git remote set-url <remote_name> <ssh_remote_url>

git push -f origin main

# Commands (Starting) ->
cd fundamental

 git --version

 git config --global user.name "YourUserName"

git config --global user.email "your.email@example.com"

git config --global user.name

git config --global user.email

 git checkout -b "Testing" // Branch Name

git init

git status

git add . (Add all the files) OR git add <filename>

git commit -m "Hey i'm pracicing"

### Now do some changes.................

git add .

git status

git commit "Modified changed"

git revert //to revert the changes

git log --oneline //to see changes

git reset --hard <number_from_git log --online> //to revert the changes

git remote add origin <link>

git branch -M main

git push -f origin main

 # Commands (Adv) ->

 touch main.py

 git status

 git add main.py

 git add .

 git commit -m "Initial commit"

 git merge

 ## Linux/Unix ->
 touch //Create a file

 mkdir // Create a folder

 rm <filename> // Delete a file

 rm -rf <foldername> // Delete a folder

 cat // See the content in a file

 nano/vi main.py // To update the content in a file

 ls // List down all the content of the current directory

 # All in one

 # Initialize a new Git repository
git init 

# Clone a remote Git repository
git clone [repository URL] 

# Stage a file for commit
git add [file] 

# Commit changes with a message
git commit -m "Commit message" 

# Check the status of your working directory
git status 

# View the commit history
git log 

# List all local branches
git branch 

# Create a new branch
git branch [branch name] 

# Switch to a different branch
git checkout [branch name] 

# Merge changes from one branch into the current branch
git merge [branch name] 

# Fetch and merge changes from a remote repository
git pull 

# Push commits to a remote repository
git push 

# List remote repositories
git remote -v 

# Fetch changes from a remote repository
git fetch [remote] 

# Show the differences between your working directory and the last commit
git diff // VVI

# Unstage a file that was previously staged
git reset [file] 

# Reset your repository to a specific commit
git reset --hard [commit hash] 

# Temporarily save changes in a "stash"
git stash 

# Create a new tag for a specific commit
git tag [tag name] 

# Add a new remote repository
git remote add [name] [URL]


 # Git workflow
 ![Alt text](image.png)

 



