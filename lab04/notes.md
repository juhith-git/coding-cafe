1)The --global flag saves your Git username and email for all projects on your computer. If you leave it out, those settings will only apply to the specific repository you are currently in.
2)The hidden .git folder appeared because ls -a shows hidden files starting with a dot.
3) 4 and nothing apart from what i have written.
4).The massive list of untracked files from the .venv folder disappeared from the output. Because you added it to the .gitignore file, Git is now ignoring that folder and no longer offers to track its contents.
5)The .gitignore file should be committed, not ignored. It is an important configuration file, and committing it ensures that anyone else working on the repository will share the exact same rules for which files to ignore.
6)In the `git status` output, `README.md` moved from the untracked files heading to the changes to be commited heading. In the three-places model, this means the file was successfully moved from your working directory into the staging area.
7)After the commit, Git printed the branch name, a short commit hash (4d3300e), the commit message, and a list of the newly created files. It explicitly stated that 6 files changed.
8)The first seven characters are called the short commit hash (or commit ID). They act as a unique identifier for that specific commit, allowing you to easily reference, track, or revert to that exact saved version of your project's history.
9)
