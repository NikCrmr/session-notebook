---

**\*\***:\***_GIT-CHEATSHEET_**::::\*\*\*\*

---

Creating local repositories

To turn a folder into a git repository you need the following git command:

cd path/to/my/folder
git init
❗️ Do not initialize a git repository inside another git repository!

---

To check if a folder has already been initialized you can run the following git command

git status

---

git status --------- List all files that have changed and their state
git add <filename> --- Add a file to the stage
git commit -m ------ "add foo" Create a commit including all staged files
git log --oneline -- Show the commit history

---

Using commits as backups

You can always return to the last committed state of the entire project:

git restore .
You can also restore individual files:

git restore <filename>
