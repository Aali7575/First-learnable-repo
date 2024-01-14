# First-learnable-repo
This is the first learnable repo we have created so far. Super excited!

# Explain version control.
Version control enables tracking the history of files, code and documents as they change, and allows coordinating work between multiple contributors and sharing an organized record of changes. It helps organize collaborative work and prevent loss of information over time.

# Explain difference between git and github
Git is a version control system. It is software local to your computer that lets you manage and keep track of changes to files.GitHub is a hosting service for Git repositories. It lives remotely on the internet.

# List 3 other github alternatives
1. Gitlab
2. Bitbucket
3. Azure DevOps

# Explain the difference between git fetch and git pull
git fetch:
1. Only downloads latest changes from the remote repository (like origin) to your local repository
2. Does not merge or update your local files
3. Useful to inspect what has changed in the remote without changing your local work

git pull:
1. Downloads AND merges the latest changes from the remote repository
2. Downloads (fetches) and merges (pulls) the changes into your current local branch
3. Useful to sync your local files and work with the remote repository changes

# Explain in simple terms git rebase and the command for it
Git rebase takes commits that were developed in one branch and replays them to another branch, like rewriting history.
The git rebase command:

git rebase branch_being_rebased_onto

# Explain in simple terms git cherry-pick and the command for it 
Git cherry-pick allows you to take individual commits from one branch and apply them to another branch without merging the branches.

The git cherry-pick command:

git cherry-pick <commit hash>
