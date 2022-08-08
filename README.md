# The-ultimate-GIt-Cheatsheet
# Downloading & Initialization
1. Initialize an existing directory as Git repository
    
        git init
2. Clone a repository that already eixts on Github,including all of the files,branches and commits
        
        git clone [repo_url]
3. After using the git init command, link the local repository to an empty Github repository 
        
        git remote add origin [url]
# SETUP CREDENTIALS
1. Set a username
    
        git config --global use.name "[firstname lastname]"
2. set an e-mail address
    
        git config --global user.email "[email address]"
# BRANCHES
1. List your branches & check active branch
    
        git branch
2. crate a new branch
    
        git branch [branch-name]
3. create a new branch & switch to that branch (one command only)
    
        git checkout -b [branch-name]
4. Delete specific branch 
    
        git branch -d [branch-name]
# STAGE & SNAPSHOT
1. show modified files in working directory ,staged for your next commit

        git status
2. Add a file as it looks now to you next commit (stage)
    
        git add [file-name]
3. Add all changed files to staging area
    
        git add
4. Commit your staged content as new commit snapshot
    
        git commit -m "[message]"
5. Fetch and merge any commits from the tracking remote branch
    
        git pull origin <branch-name>
6. Transmit local branch commits to remote repository branch
    
        git push origin <branch-name>
7. synchronise your local repository with the remote repository
    
        git fetch

# MERGING
1. Merge a remote branch into your current branch to bring it up to date 
    
        git merge <branch-name>
# REDO COMMITS 
1. Reset staging area to match most recent commit but leave the working directory unchanged 

        git reset
2. Reset staging area and working directory to match most recent commit and overwrite all changes in the working directory
    
        git reset --hard
3. Create a new commit,reverting changes from the specified commit.

        git revert <commit>

# TEMPORARY COMMITS
1. put current changes in your working directory into stash for later use 
    
        git stash
2. Apply stored stash content into working directory, and clear stash
 
        git stash pop
3. Delete a specific stash from all your previous stashes
    
        git stash drop
    
# KEEP LEARNING !    
    
    
