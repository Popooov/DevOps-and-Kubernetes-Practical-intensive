# new-project

## Instructions

### Step 1: Create a new directory
```
mkdir new-project
```
### Step 2: Change into the directory
```
cd new-project
```

### Step 3: Initialize a Git repository
```
git init
```
### Step 4: Create README.md file and add initial text
```
echo "# New Project" > README.md
```
### Step 5: Stage README.md for commit
```
git add README.md
```
### Step 6: Commit the changes with the message "init"
```
git commit -m "init"
```
### Step 7: Create and switch to the "development" branch
```
git branch development
git checkout development
```
### Step 8: Add instructions to the README.md file
```
echo "## Instructions" >> README.md
```
Stage README.md for commit
```
git add README.md
```
### Step 9: Commit the changes in the "development" branch
```
git commit -m "Add instructions for development"
```
### Step 10: Merge changes from "development" into "main" branch
```
git checkout main
git merge development
```
### Step 11: Check the status to ensure everything is up to date
```
git status
```
### Step 12: Commit the changes
```
git commit -m "Merge development into main"
```