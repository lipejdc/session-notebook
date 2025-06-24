Please follow this workflow when working on challenges. It helps you practicing the git branches commands every day. Practice makes perfect!

1. In the local `web-challenges` repository, make sure you are on the `main` branch.
2. Create a folder with the name of the session. For example, `mkdir css-basic`.
3. Navigate to the folder created in step 2 `cd css-basics`.
4. Once you are inside the folder, download **the first** challenge (using the npx command). This creates a new folder belonging to that challenge.
5. Change into that folder, e.g. `cd css-basics-pink-box`.
6. Open that folder with Visual Studio Code `code .`.

From here it's easiest to use the Visual Studio Code Terminal `CMD + J` on MacOS or `STRG + J` on Windows.

7. Switch to a new branch for this challenge, e.g. `git switch -c feature/css-basics-pink-box`. 
8. Do an initial commit `git add .` `git commit -m "initial commit"`.
9. Work on the challenge. You can do some commits from time to time.
10. Once you have finished the challenge commit and push all changes to Github `git push -u origin feature/css-basics-pink-box`.

11. Open a browser and go to your Github repository. Create a new Pull Request.
12. Copy the URL from the browser and paste it into the Discord Solution thread.
13. Merge the PR on Github and delete the feature branch.

14. In VS Code switch to the main branch `git switch main`.
15. Pull the changes from Github `git pull`.
16. Delete the local feature branch `git branch -d feature/css-basics-pink-box`.

17. Close VS Code and in your terminal change into the sessions folder. Repeat all steps with the next challenge.
