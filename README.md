# Common-Git-Commands
Created as reference for myself
## Start in the main repository folder (only once)
git clone [http URL]

## Update the local repository
git pull

## Show added/changed files
git status

## Add files
git add -h (help for options)

git add -u (add modified & remove deleted files--won't add new files) *My favorite

git add -A (won't delete)

git add .

git add "file name"

## Commit to local master
git commit -m "Type a message here."

## Push local commits to master
git push -u origin master

## Reset
git reset file (resets file to master)
