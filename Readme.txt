PS C:\Users\Admin\Documents\AL\ALJRV_GIT_LAB> git status
fatal: not a git repository (or any of the parent directories): .git
PS C:\Users\Admin\Documents\AL\ALJRV_GIT_LAB> E432DHDH4git init
E432DHDH4git : The term 'E432DHDH4git' is not recognized as the name of a cmdlet, 
function, script file, or operable program. Check the spelling of the name, or if a 
path was included, verify that the path is correct and try again.
At line:1 char:1
+ E432DHDH4git init
+ ~~~~~~~~~~~~
    + CategoryInfo          : ObjectNotFound: (E432DHDH4git:String) [], CommandNotF 
   oundException
    + FullyQualifiedErrorId : CommandNotFoundException
 
PS C:\Users\Admin\Documents\AL\ALJRV_GIT_LAB> 
PS C:\Users\Admin\Documents\AL\ALJRV_GIT_LAB> 
PS C:\Users\Admin\Documents\AL\ALJRV_GIT_LAB> 
PS C:\Users\Admin\Documents\AL\ALJRV_GIT_LAB> 
PS C:\Users\Admin\Documents\AL\ALJRV_GIT_LAB> 
PS C:\Users\Admin\Documents\AL\ALJRV_GIT_LAB> 
PS C:\Users\Admin\Documents\AL\ALJRV_GIT_LAB> 
PS C:\Users\Admin\Documents\AL\ALJRV_GIT_LAB> 
PS C:\Users\Admin\Documents\AL\ALJRV_GIT_LAB>
PS C:\Users\Admin\Documents\AL\ALJRV_GIT_LAB> 
PS C:\Users\Admin\Documents\AL\ALJRV_GIT_LAB>
PS C:\Users\Admin\Documents\AL\ALJRV_GIT_LAB> 
PS C:\Users\Admin\Documents\AL\ALJRV_GIT_LAB> 
PS C:\Users\Admin\Documents\AL\ALJRV_GIT_LAB> 
PS C:\Users\Admin\Documents\AL\ALJRV_GIT_LAB> git init
Initialized empty Git repository in C:/Users/Admin/Documents/AL/ALJRV_GIT_LAB/.git/
PS C:\Users\Admin\Documents\AL\ALJRV_GIT_LAB> git add
Nothing specified, nothing added.
hint: Maybe you wanted to say 'git add .'?
hint: Disable this message with "git config advice.addEmptyPathspec false"
PS C:\Users\Admin\Documents\AL\ALJRV_GIT_LAB> git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        .alpackages/
        .vscode/
        HelloWorld.al
        app.json

nothing added to commit but untracked files present (use "git add" to track)
PS C:\Users\Admin\Documents\AL\ALJRV_GIT_LAB> git add .
warning: in the working copy of 'HelloWorld.al', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'app.json', LF will be replaced by CRLF the next time Git touches it
PS C:\Users\Admin\Documents\AL\ALJRV_GIT_LAB> git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   .alpackages/Microsoft_Application_25.1.25873.26186.app
        new file:   .alpackages/Microsoft_Base Application_25.1.25873.26550.app      
        new file:   .alpackages/Microsoft_Business Foundation_25.1.25873.26186.app   
        new file:   .alpackages/Microsoft_System Application_25.1.25873.26186.app
        new file:   .alpackages/Microsoft_System_25.0.25866.0.app
        new file:   .vscode/launch.json
        new file:   HelloWorld.al
        new file:   app.json

PS C:\Users\Admin\Documents\AL\ALJRV_GIT_LAB> git commit -m "init commit"
[master (root-commit) bbe627a] init commit
 8 files changed, 61 insertions(+)
 create mode 100644 .alpackages/Microsoft_Application_25.1.25873.26186.app
 create mode 100644 .alpackages/Microsoft_Base Application_25.1.25873.26550.app      
 create mode 100644 .alpackages/Microsoft_Business Foundation_25.1.25873.26186.app   
 create mode 100644 .alpackages/Microsoft_System Application_25.1.25873.26186.app    
 create mode 100644 .alpackages/Microsoft_System_25.0.25866.0.app
 create mode 100644 .vscode/launch.json
 create mode 100644 HelloWorld.al
 create mode 100644 app.json
PS C:\Users\Admin\Documents\AL\ALJRV_GIT_LAB> git remote add origin https://github.com/jrvenzra/Day5-Mb820.git
PS C:\Users\Admin\Documents\AL\ALJRV_GIT_LAB> git push --all
fatal: unable to access 'https://github.com/jrvenzra/Day5-Mb820.git/': Could not resolve host: github.com
PS C:\Users\Admin\Documents\AL\ALJRV_GIT_LAB> git remote add origin https://github.com/jrvenzra/Day5-Mb820.git
error: remote origin already exists.
PS C:\Users\Admin\Documents\AL\ALJRV_GIT_LAB> git push --all                         
info: please complete authentication in your browser...
Enumerating objects: 12, done.
Counting objects: 100% (12/12), done.
Delta compression using up to 2 threads
Compressing objects: 100% (11/11), done.
Writing objects: 100% (12/12), 49.79 MiB | 5.58 MiB/s, done.
Total 12 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), done.
To https://github.com/jrvenzra/Day5-Mb820.git
 * [new branch]      master -> master
PS C:\Users\Admin\Documents\AL\ALJRV_GIT_LAB> 