// Lists all branches

1. git branch

// Create new branch

1. git branch BRANCH_NAME
2. git checkout BRANCH_NAME
3. git branch // \* should appear before newly created branch

// Push changes to repository, ensure you are on respective branch

1. git status // Lists all changed files
2. git add .
3. git commit -m "COMMIT_MESSAGE"
4. git push origin BRANCH_NAME
