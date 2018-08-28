C:\Users\prash\angular_playground>browser-sync start --server --directory --files "**.*"



C:\Users\prash\angular_playground>history
'history' is not recognized as an internal or external command,
operable program or batch file.

C:\Users\prash\angular_playground>%history
'%history' is not recognized as an internal or external command,
operable program or batch file.

C:\Users\prash\angular_playground>browser-sync start --server --directory --files "**.*"
[Browsersync] Access URLs:
 ----------------------------------------
       Local: http://localhost:3000
    External: http://192.168.150.140:3000
 ----------------------------------------
          UI: http://localhost:3001
 UI External: http://192.168.150.140:3001
 ----------------------------------------
[Browsersync] Serving files from: ./
[Browsersync] Watching files...
[Browsersync] Reloading Browsers...
^CTerminate batch job (Y/N)?
Terminate batch job (Y/N)? y

C:\Users\prash\angular_playground>git status
On branch master
Your branch is up to date with 'origin/master'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git checkout -- <file>..." to discard changes in working directory)

        modified:   index.html

Untracked files:
  (use "git add <file>..." to include in what will be committed)

        readme.txt

no changes added to commit (use "git add" and/or "git commit -a")

C:\Users\prash\angular_playground>git add .

C:\Users\prash\angular_playground>git status
On branch master
Your branch is up to date with 'origin/master'.

Changes to be committed:
  (use "git reset HEAD <file>..." to unstage)

        modified:   index.html
        new file:   readme.txt


C:\Users\prash\angular_playground>git commit -m "updates"
[master d072848] updates
 2 files changed, 2 insertions(+), 1 deletion(-)
 create mode 100644 readme.txt

C:\Users\prash\angular_playground>git push .
Everything up-to-date

C:\Users\prash\angular_playground>git status
On branch master
Your branch is ahead of 'origin/master' by 1 commit.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

C:\Users\prash\angular_playground>git push .
Everything up-to-date

C:\Users\prash\angular_playground>git config --global push.default simple

C:\Users\prash\angular_playground>
