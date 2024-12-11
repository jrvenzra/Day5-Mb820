Set username in Git.

git config --global user.name "yourusername"

Set an email address in Git.

git config --global user.email "email@youremail.com"

Verify that Git is Linked to your Github
$ git config --global --list


Delete the remote branch (usually <remote> is origin):
git push <remote> --delete <branch>
Delete the local branch:
git branch --delete <branch>


How can you remove a Git user's details from the terminal?

git config --global --unset user.name
git config --global --set user.email
git config --global user.clear
git reset --user


git remote remove origin

OR 

git remote rm origin

To modify the URL:

git remote set-URL origin "new URL"
