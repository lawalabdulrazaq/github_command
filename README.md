To update your code on GitHub after making changes, you'll need to follow these basic Git commands. Here's the process step by step:

1. **Navigate to your project folder** (where your code is located) in your terminal:
   ```bash
   cd /path/to/your/repository
   ```

2. **Check the status** to see the changes you've made:
   ```bash
   git status
   ```

3. **Add the changed files** to the staging area:
   - To add all changes (modified, added, or deleted files):
     ```bash
     git add .
     ```
   - Or if you want to add specific files, specify them:
     ```bash
     git add filename1 filename2
     ```

4. **Commit the changes** with a meaningful message:
   ```bash
   git commit -m "Your commit message describing the changes"
   ```

5. **Pull the latest changes** from the remote repository (optional but recommended to avoid conflicts if others have updated the repo):
   ```bash
   git pull origin main
   ```
   (Replace `main` with the branch name you are working on if it's different.)

6. **Push the changes** to GitHub:
   ```bash
   git push origin main
   ```
   (Replace `main` with your branch name if necessary.)

That's it! Your changes should now be updated in your GitHub repository.
