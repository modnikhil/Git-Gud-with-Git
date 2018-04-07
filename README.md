# Git-Gud-with-Git
How to add your own file to the Git-Gud-with-Git Repository
1. Use terminal to navigate to a folder that you would like to save this project in
2. Open https://github.com/modnikhil/Git-Gud-with-Git/ in a browser
3. In your terminal, run ```git clone https://github.com/modnikhil/Git-Gud-with-Git/```
4. Open up TextEdit (Mac) or NotePad (Windows)
5. Edit and save a file as a .txt to the Git-Gud-with-Git folder
6. Go back to terminal and run ```cd Git-Gud-with-Git```
   * This now puts you in the correct directory!
7. Run ```git status```
   * This should show you the .txt file you saved earlier as an "Untracked" file. This means that we haven't told Git that we'd like to include this file in our project.
8. To include the text file, we can run ```git add <file name>```
   * If we would later like to remove this file and untrack it, we can run ```git rm <file name>```
9. All of our files/changes are now in staging and ready to be committed to our local repository. By committing, we are taking a "snapshot" of what our code looks like at this moment so we can look back on it later. To do so, we run ```git commit -m "<Enter Commit Message here>```
   * While the ```-m``` flag is optional, it's highly encouraged to provide commit messages to all your commits
10. Great! All of our changes have been committed to our local repo. It's time to push our changes from our local repo to the remote repo so everyone can see the wonderful additions we've made! Pushing is simple, just run ```git push```.
   * You may get an error message along the lines of "error: failed to push some refs to 'https://github.com/........'". This is a very common error, so don't worry! Git is just telling us that our current repository and the remote repository aren't up-to-date with each other. This means that someone else must've pushed some changes while you were still working! To resolve this, simply run ```git pull``` and allow Git to merge the changes for you. Pulling brings the new changes made in the remote repository to your local repository! Then just ```git push``` again and you'll be good to go!
11. Now it's time to view your masterpiece! Go to https://github.com/modnikhil/Git-Gud-with-Git and take a look at the new file you just created.

Congrats! You're on your way to being a Git wizard!
