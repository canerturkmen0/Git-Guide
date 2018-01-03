# Some Basic Terminal Commands :hatched_chick:
```
mkdir test -> creates a folder called test
touch index.html -> creates a document callede index.html
Atom index.html -> runs the index.html with Atom
rm index.html -> deletes the document called index.html
rmdir test -> deletes the folder called test
```

# Git Configuration :chicken:
> // will be updated

# Initializing the Git (Creating repository) :rooster:
If you want to use git for a project, you need to create a repository. Thus, go to directory with terminal and run 'git init' command.

# Staging Files :cow2:
```
git status -> shows the items are in staging area or not.
git add index.html -> adds index.html to staging area
git rm --cached index.html -> removes from the staging area
git add . -> adds every single file to staging area

In staging area, they are ready to be committed. Why do we add them to staging area?
  -Security
  -stage,commit,stage,commit (split our work,seperate commits,seperate changes)
```
# Making Commits :ram:
```
git commit -m "added index and styles files"  -> makes commit with message
git log -> Shows commit history with details
git log --oneline -> Shows commit history line by line
```
# Undoing :goat:
```
git checkout af67fg8f -> shows the commit that has 'af67fg8f' id (read only)
git checkout master

git revert d6318fs (undo a commit)
:wq new message? no -> does not delete the commit,
it adds a new commit that 'commit name'
we still have access to this commit

git reset af461fa       -> deletes all commit until 'af461fa' id
git reset af461fa --hard

> We don't have to do git add while undoing
```
