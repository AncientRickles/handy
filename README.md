# Handy Scripts Repo

This is my repoistory of handy scripts.  Current contents:

- mkpy
    - USAGE: mkpy <filename>
    - A simple bash script that makes a python3 script, marks it as executable by the user, echos in the proper hashbang and launches it in Vim.

- syncgit
    - USAGE: syncgit (from local repo directory)
    - The purpose of this script is to sync your fork with the upstream repo.
    - This script fetches data from the upstream repo, merges that data into origin/master, then pushes the changes to remote origin
    - Remember to configure the upstream repo on your local repo:
    
        `git remote add upstream <repo>`
