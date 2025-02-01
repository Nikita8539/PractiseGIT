PS D:\GIT> git

'git help -a' and 'git help -g' list available subcommands and some
concept guides. See 'git help <command>' or 'git help <concept>'
to read about a specific subcommand or concept.

PS D:\GIT> git init
Initialized empty Git repository in D:/GIT/.git/

PS D:\GIT> git add README.md

PS D:\GIT> git commit -m "First Commit"
[master (root-commit) 5ba710e] First Commit
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 README.md

PS D:\GIT> git branch -M main
PS D:\GIT> git branch
* main
PS D:\GIT> git remote add origin https://github.com/Nikita8539/PractiseGIT.git
PS D:\GIT> git remote -v
origin  https://github.com/Nikita8539/PractiseGIT.git (fetch)
origin  https://github.com/Nikita8539/PractiseGIT.git (push)

PS D:\GIT> git push origin main
info: please complete authentication in your browser...
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 222 bytes | 222.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/Nikita8539/PractiseGIT.git
 * [new branch]      main -> main

 
PS D:\GIT> git add .
PS D:\GIT> git commit -m "Used Commands added"
[main 1291300] Used Commands added
 1 file changed, 32 insertions(+)
PS D:\GIT> git push -u origin main