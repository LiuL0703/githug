# Githug
# #20
Name: commit_in_future
Commit your changes with the future date (e.g. tomorrow).

### ➜  git commit --date="Sat Dec 19 2017 14:39:36 GMT+0800 (CST)" -m 'commit_in_19th'
# #21
Name: reset
There are two files to be committed.  The goal was to add each file as a separate commit, however both were added by accident.  Unstage the file `to_commit_second.rb` using the reset command (don't commit anything).

### ➜  git reset HEAD to_commit_second.rb
# #22
Name: reset_soft
You committed too soon. Now you want to undo the last commit, while keeping the index

### ➜  git_hug git reset --soft HEAD^

# #23
Name: checkout_file
A file has been modified, but you don't want to keep the modification.  Checkout the `config.rb` file from the last commit.

### ➜  git_hug git checkout config.rb
# 24 
Name: remote
This project has a remote repository.  Identify it.

### ➜  git remote

# #25  
Name: remote_url
The remote repositories have a url associated to them.  Please enter the url of remote_location.

### ➜ git remote get-url --all remote_location
