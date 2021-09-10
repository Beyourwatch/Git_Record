# Git_Record


# 看版本 git log

Boqie Zhang@DESKTOP-LDM2ITI MINGW64 ~/source/repos/GitHUB/C-_MV_SelectNIC (main)
$ git log --oneline 

28f8caf (HEAD -> main, origin/main, origin/HEAD) change one.txt

441d349 add code

670aed8 Initial commit

# 退回版本 git log

Boqie Zhang@DESKTOP-LDM2ITI MINGW64 ~/source/repos/GitHUB/C-_MV_SelectNIC (main) 
$ git reset --hard HEAD@{1}

HEAD is now at 441d349 add code


# 退回后重新发送到remote， 需要 -f, 因为版本落后

Boqie Zhang@DESKTOP-LDM2ITI MINGW64 ~/source/repos/GitHUB/C-_MV_SelectNIC (main)
$ git push

To github.com:Beyourwatch/C-_MV_SelectNIC.git

 ! [rejected]        main -> main (non-fast-forward)
 
error: failed to push some refs to 'github.com:Beyourwatch/C-_MV_SelectNIC.git'

hint: Updates were rejected because the tip of your current branch is behind

hint: its remote counterpart. Integrate the remote changes (e.g.

hint: 'git pull ...') before pushing again.

hint: See the 'Note about fast-forwards' in 'git push --help' for details.


Boqie Zhang@DESKTOP-LDM2ITI MINGW64 ~/source/repos/GitHUB/C-_MV_SelectNIC (main)
$ git push -f

Total 0 (delta 0), reused 0 (delta 0), pack-reused 0

To github.com:Beyourwatch/C-_MV_SelectNIC.git

 + 28f8caf...441d349 main -> main (forced update)
 


# 手动在网页上，或者别人修改后，需要更新本地 git pull
Boqie Zhang@DESKTOP-LDM2ITI MINGW64 ~/source/repos/GitHUB/Git_Record (main)
$ git pull

remote: Enumerating objects: 5, done.

remote: Counting objects: 100% (5/5), done.

remote: Compressing objects: 100% (2/2), done.

remote: Total 3 (delta 1), reused 0 (delta 0), pack-reused 0

Unpacking objects: 100% (3/3), 697 bytes | 4.00 KiB/s, done.

From github.com:Beyourwatch/Git_Record

   29768c7..06f1476  main       -> origin/main
   
Updating 29768c7..06f1476

Fast-forward

 README.md | 6 +++++-
 
 1 file changed, 5 insertions(+), 1 deletion(-)
 
 



