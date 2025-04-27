1. Initialize Git Repository   
git init # Initialize a new Git repository

3. Check Current Status
git status # See changes staged, unstaged, and untracked files

4. Add Files to Staging Area
git add nibbi.txt # Stage nibbi.txt for commit

git add nibba.txt # Stage nibba.txt for commit

git add nibbu.txt # Stage nibbu.txt for commit

4. Commit Changes
git commit -m "adding nibba nibbi" # Commit staged files with a message

git commit -m "Adding new changes to nibbi" # Commit updates

git commit -m "adding changes to nibbi" # Another commit message

git commit -m "adding changes to nibba" # Commit changes for nibba.txt

git commit -m "added new changes to nibbi" # Updated nibbi.txt

git commit -m "adding nibbu" # Committing new file nibbu.txt

5. Configure Git User Information
git config --global user.name "ArvindTatu2" # Set Git username globally

git config --global user.email "arvindtatu77@gmail.com" # Set Git email globally

git config --global --edit # Edit Git global configuration manually

6. View Commit History
git log # Show full commit history

git log --oneline # Show condensed commit history (one line per commit)

7. Branching and Switching Branches
git branch # List all local branches

git checkout -b dev # Create and switch to new branch 'dev'

git checkout master # Switch back to 'master' branch

git checkout dev # Switch to 'dev' branch

8. Common Typing Mistakes (Ignore)
git cimmit -m "adding changes to nibbi" # Typo: should be git commit
