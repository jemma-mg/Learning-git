# Example Repository <!-- (# - H1 header) -->

This is a sample repo, hello coders!

Adding another change

<!-- (.md - markdown) -->
 
 ### Adding changes
 
 git clone "repo_path" ---> git add "files/directories" ---> git commit -m "commit_message" ---> git push origin "main/branch_name/master"
 git status, git log

git checkout {branchname}

#### Add the remote, call it "upstream":

git remote add upstream <https://github.com/whoever/whatever.git>

#### Fetch all the branches of that remote into remote-tracking branches

git fetch upstream

#### Make sure that you're on your master branch:

git checkout master

#### Rewrite your master branch so that any commits of yours that aren't already in upstream/master are replayed on top of that other branch:

git rebase upstream/master
