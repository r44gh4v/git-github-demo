# git-github-demo

## my git cli process

PS D:\Coding\!DevOps\git github demo> git status                     
fatal: not a git repository (or any of the parent directories): .git
PS D:\Coding\!DevOps\git github demo> git init  
Initialized empty Git repository in D:/Coding/!DevOps/git github demo/.git/
PS D:\Coding\!DevOps\git github demo> git status
On branch main

No commits yet

nothing to commit (create/copy files and use "git add" to track)
PS D:\Coding\!DevOps\git github demo> echo "# git-github-demo" >> README.md
PS D:\Coding\!DevOps\git github demo> git init  
Reinitialized existing Git repository in D:/Coding/!DevOps/git github demo/.git/
PS D:\Coding\!DevOps\git github demo> git add .
PS D:\Coding\!DevOps\git github demo> git status
On branch main

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   README.md

PS D:\Coding\!DevOps\git github demo> git commit -m "first commit"          
[main (root-commit) 0069e28] first commit
 1 file changed, 1 insertion(+)
 create mode 100644 README.md
PS D:\Coding\!DevOps\git github demo> git branch -M main          
PS D:\Coding\!DevOps\git github demo> git remote add origin https://github.com/r44gh4v/git-github-demo.git
PS D:\Coding\!DevOps\git github demo> git status                            
On branch main                
nothing to commit, working tree clean
PS D:\Coding\!DevOps\git github demo> git origin
git: 'origin' is not a git command. See 'git --help'.
PS D:\Coding\!DevOps\git github demo> git status
On branch main
nothing to commit, working tree clean
PS D:\Coding\!DevOps\git github demo> git push                       
fatal: The current branch main has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin main

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.

PS D:\Coding\!DevOps\git github demo> git push -u origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 240 bytes | 240.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/r44gh4v/git-github-demo.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.