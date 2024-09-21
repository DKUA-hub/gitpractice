GIT Practice

1. Initialize folder:
git init

2. Create README file

3. Commit changes
git add .
git commit -m "<commit_message>"

4. Push your changes to remote repository
4.1. Add remote path
git remote add origin <http://github.com/.../*.git>
4.2. push updates
git push -u origin master

5. create a branch
git checkout -b <new_branch_name>

6. Add files and commit updates
git add .
git commit -m "..."

7. Push cchanges
git push -u origin <current_branch>

8. Merge changes to master
git checkout master
git merge <branch_which_is_going_to_be_merged_into_master>