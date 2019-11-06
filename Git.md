# GIT CHEAT SHEET

## Porcelain commands

###  CREATE REPOSITORIES

<dl>
    <dt>git init</dt>
    <dd>Create a new local resository</dd>
    <dt>git clone [url]</dt>
    <dd>Download a project</dd>
</dl>

###  TRACKING CHANGES

<dl>
    <dt>git add [file/folder]</dt>
    <dd>Prepare the file or folder to commit</dd>
    <dt>git status</dt>
    <dd>Show all modification to be committed</dd>
    <dt>git commit -m "[message]"</dt>
    <dd>Save changes at a point in time with a description</dd>
    <dt>git reset [file/folder]</dt>
    <dd>Remove the file or folder from staging area</dd>
</dl>

### WORKING WITH BRANCHES

<dl>
    <dt>git branch [new branch name]<dt>
    <dd>Creates a new branch</dd>
    <dt>git chechout [branch name]</dt>
    <dd>Changes the current wokining directory branch</dd>
    <dt>git merge [branch]<dt>
    <dd>Performs the merge between the current branch and the branch passed as argument</dd>
    <dt>git rebase [branch]</dt>
    <dd>Performs the merge, but recreate the history in a only branch and destroys the other</dd>
</dl>

### TEAM WORK

<dl>
    <dt>git push</dt>
    <dd>Uploads all local branch chanches to origin</dd>
    <git>git fetch</dit>
    <dd>Download all origin branch changes locally</dd>
    <dt>git pull</dt>
    <dd>Perfom a git fetch and git merge</dd>
</dl>


## Plumbing commands

<dl>
    <dt>git cat-file -p [hash object]</dt>
    <dd>Show friendly informations about a git object</dd>
    <dt>echo 'Git Cheat Sheet' | git hash-object --stdin</dt>
    <dd>Calculate the SHA1 to a input 'Git Cheat Sheet'</dd>
    <dt>git count-ojects</dt>
    <dd>Show the number of git objects</dd>
    <dt>git show-ref [branch]</dt>
    <dd>Show the commit references of a branch</dd>
</dl>
