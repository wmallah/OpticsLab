# Optics Lab
Files for optics lab

# How to use :)
First, make sure Git is installed on your computer by typing the following command into your command prompt/terminal:
```
git --version
```
If version isn't displayed, follow this [guide to install git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git), and try again:

Next, find the folder where you find to keep the repository and open it up in the termimal. In Windows, you can simply type ``cmd`` into the address bar while your folder is opened in file explorer.

# Cloning Repository
To clone this repository (file system), use the following command while in the directory you desire:
```
git clone https://github.com/user/repository
```
For this remote respository, this command becomes
```
git clone https://github.com/jmeneghini/AdvancedLab.git
```
Now you can begin editing the files in your folder, but they will not change remote repository on GitHub, yet...
When editing files on your computer, you are working with ```Working Directory``` which holds the actual files. The next step is add changed files into the ``Index``, which acts as a staging area for your files. Once the files are in the Index, you can commit them to the ``Head``, which keep tracks of the last commit you made.

# Adding and Committing
When ready to send new/changed files to remote repository, you'll first need to add the files to the index with the following command. You can repeat this command until all files are added:
```
git add <filename>
```
If you want to add all files you have added or changed, use the following command instead:
```
git add -A
```
With your files now commited to the Index, they can now be moved to the Head using the commit command. It's important to add a short message describing your changes:
```
git commit -m "Commit message"
```
# Final Step: Pushing
Once your commits are finalized, the following command will send your files to GitHub:
```
git push origin main
```
# Updating your local directory
To update your folder with all the changes people have uploaded to GitHub, use the following command:
```
git pull
```

# GUI Alternatives 
For those scared of the command line, most modern IDEs have Git implementation you could use. In addition, there is GitHub Desktop which I heard is pretty reliable

# Additional Info
For additional info that isn't 100 percent necesarry for this to work but is extremely useful, check out this [link](https://rogerdudler.github.io/git-guide/)
