## Manual publishing

1. On Github.com create an empty repository
   - be sure not to click "add ReadMe.md"
2. On your computer at the terminal create a remote named `origin` that points to the url of the empty repository
   ```
   git remote add origin [url]
   ```
3. Verify the remote was created by listing the remotes.
    ```
    git remote -v
    ```
4. Push/Publish your code to the remote repository on Github
   ```
   git push [remote name] [branch name]
   git push origin main
   ```

> Optional/Bonus: push a feature branch to Github
