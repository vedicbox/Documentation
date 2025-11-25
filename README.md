# Git Workflow Documentation

## Create a New Branch

1. Switch to master branch
    ```bash
    git switch master
    ```

2. Pull latest changes
    ```bash
    git pull origin master
    ```

3. Create and checkout new branch
    ```bash
    git checkout -b <branch-name>
    ```

## Merge Master Code to Current Branch

Check current status
    ```bash
    git status
    ```

### If you have uncommitted changes:

1. Stage and commit your changes
    ```bash
    git add .
    git commit -m "your commit message"
    ```

2. Pull latest master code
    ```bash
    git pull origin master
    ```

### If you have no changes:

1. Pull latest master code
    ```bash
    git pull origin master
    ```

## Push Code to Current Branch

1. Stage and commit your changes
    ```bash
    git add .
    git commit -m "your commit message"
    git push origin <branch-name>
    ```
