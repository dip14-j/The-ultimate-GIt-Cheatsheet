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
