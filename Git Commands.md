**📝 Git Command Cheat Sheet**

**Essential Commands for Modern Version Control**

**🚀 Getting Started**

- **git init** | Initialize a new local repository.
- **git clone &lt;url&gt;** | Copy a remote repository to your machine.
- **git config --global user.name "Name"** | Set your commit identity.

**🛠️ The Daily Workflow**

- **git status** | Check the state of your working directory.
- **git add &lt;file&gt;** | Stage specific changes for the next commit.
- **git add .** | Stage **all** changed files in the current directory.
- **git commit -m "Message"** | Save your staged snapshot to history.
- **git push &lt;remote&gt; &lt;branch&gt;** | Upload local commits to the server.
- **git pull** | Fetch and merge changes from the remote server.

**🌿 Branching & Collaboration**

- **git branch** | List all local branches.
- **git checkout -b &lt;name&gt;** | Create a new branch and switch to it.
- **git checkout &lt;branch&gt;** | Switch to an existing branch.
- **git merge &lt;branch&gt;** | Merge the specified branch into your current one.
- **git fetch** | Download objects/refs from remote (without merging).

**🔍 Inspection & Logs**

- **git log --oneline** | View a simplified, clickable commit history.
- **git diff** | See unstaged changes compared to the last commit.
- **git diff --staged** | See changes that are ready to be committed.
- **git remote -v** | List your linked remote repositories (URLs).

**🚑 The "Undo" Palette**

- **git reset --soft HEAD~1** | Undo the last commit; **keep** your changes staged.
- **git reset --hard HEAD~1** | Undo the last commit; **destroy** all changes.
- **git restore &lt;file&gt;** | Discard local changes and revert to the last commit.
- **git stash** | Safely tuck away uncommitted changes for later.
- **git stash pop** | Bring your stashed changes back to the surface.

**💡 Pro-Tips for the Terminal**

- **Tab Completion:** Start typing a command or branch name and hit Tab to finish it.
- **The "Safety" Pull:** Always git pull before you start a new branch to ensure you're building on the latest code.
- **Atomic Commits:** Keep commits small and focused on one task (e.g., "Fix header styling," not "Updated CSS and added 5 features").

An excellent resource for enterprise app packaging with a collection of nearly 9,000 apps. The site catalogs critical app info including install strings
