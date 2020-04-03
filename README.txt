# git_command
# this repo hold some useful git command

# removing file from the entire repo by (rewriting the entire tree)

  #to remove from the start 
    git filter-branch --tree-filter 'rm -rf path/from/root' HEAD
  #to remove from a specific commit
    git filter-branch --tree-filter 'rm -rf path/from/root' 7b3072c..HEAD
