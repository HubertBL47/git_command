# git_command
# this repo hold some useful git command that i keep searching on goolgle

# removing file from the entire repo by (rewriting the entire tree)

  #to remove from the start 
    git filter-branch --tree-filter 'rm -rf path/from/root' HEAD
  #to remove from a specific commit
    git filter-branch --tree-filter 'rm -rf path/from/root' 7b3072c..HEAD


# get remote url
git config --get remote.origin.url

#extract file from git stash
git checkout stash@{0} -- <filename>

