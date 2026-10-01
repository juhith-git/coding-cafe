1)The --global flag saves your Git username and email for all projects on your computer. If you leave it out, those settings will only apply to the specific repository you are currently in.
2)The hidden .git folder appeared because ls -a shows hidden files starting with a dot.
3) 4 and nothing apart from what i have written.
4).The massive list of untracked files from the .venv folder disappeared from the output. Because you added it to the .gitignore file, Git is now ignoring that folder and no longer offers to track its contents.
5)The .gitignore file should be committed, not ignored. It is an important configuration file, and committing it ensures that anyone else working on the repository will share the exact same rules for which files to ignore.
6)In the `git status` output, `README.md` moved from the untracked files heading to the changes to be commited heading. In the three-places model, this means the file was successfully moved from your working directory into the staging area.
7)After the commit, Git printed the branch name, a short commit hash (4d3300e), the commit message, and a list of the newly created files. It explicitly stated that 6 files changed.
8)The first seven characters are called the short commit hash (or commit ID). They act as a unique identifier for that specific commit, allowing you to easily reference, track, or revert to that exact saved version of your project's history.
9)git status, git add, git commit, git log.
10)GitHub automatically displays README.md on the front page of your repository so visitors can instantly see what your project is about.
11)It saved a secure access token on my computer, allowing Git to automatically verify my identity without asking for my password every time I push.
12)the README.md file is being displayed because to let let anyone who sees the repository understand project first.
13)No, pushing did not change your local history at all.
14)If my repository is private on GitHub, it acts as a secure cloud backup that only I and the people I explicitly invite—like my TAs—can see. If it didn't exist on GitHub at all, it would only live locally on my computer, meaning absolutely no one else could access it and I would have no backup.

