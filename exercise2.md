# Important Git commands

Here is a list of the most important Git commands and their functions.

| Command | Description |
| ------ | ------ |
| `git config` | Used to configure a Git installation or an individual repository (e.g. user information, settings, the behavior of the repository, ...). |
| `git init` | Creates a new Git repository – transforms a current directory into a Git repository. |
| `git commit` | Creates a snapshot of the changes to the files in a Git repository. This creates a new version of the repository that preserves those changes. Commits are considered "safe" versions of a project – so Git only makes changes to them when explicitly instructed to do so. |
| `git status` | Displays the current status of the Git repository. Provides information about which files in the repository have been modified, added, or deleted, and whether or not they are already marked for commit. Git distinguishes between three different states: `untracked` for files that are new and have never been added to the repository, `modified` for files that have been modified in the working directory, but are not yet marked for commit, and `staged` for files that have been added to the staging area and are ready for a commit. |
| `git add` | Changes to files in the working directory are marked for the next commit and added to the staging area. Files marked as `staged` can be considered for the next commit and added to the repository with `git commit`. |
| `git log` | Displays a chronological list of all commits in the current branch of the Git repository. |
| `git diff` | Shows differences between the working directory and the index (staging area) or between different commits in the Git repository in the form of a list of changes. |
| `git pull` | Fetches all changes from a remote repository - which is usually hosted on a central server like GitHub or GitLab - and merges them into the local branch. `git pull` is a combination of the `git fetch` and `git merge` commands. |
| `git push` | Uploads all local commits to a remote repository. |