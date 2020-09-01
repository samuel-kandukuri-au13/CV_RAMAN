# DEMO for WEEk02 Day02

# DEscription for the CV_RAMAN
samuel@Sam MINGW64 ~
$ cd CV_RAMAN
bash: cd: CV_RAMAN: No such file or directory

samuel@Sam MINGW64 ~
$ mkdir CV_RAMAN

samuel@Sam MINGW64 ~
$ cd CV_RAMAN

samuel@Sam MINGW64 ~/CV_RAMAN
$ git init
Initialized empty Git repository in C:/Users/samuel/CV_RAMAN/.git/

samuel@Sam MINGW64 ~/CV_RAMAN (master)
$ git clone https://github.com/samuel-kandukuri-au13/CV_RAMAN.git first_repo
Cloning into 'first_repo'...
warning: You appear to have cloned an empty repository.

samuel@Sam MINGW64 ~/CV_RAMAN (master)
$ touch README.md

samuel@Sam MINGW64 ~/CV_RAMAN (master)
$ code README.md

samuel@Sam MINGW64 ~/CV_RAMAN (master)
$ cd first_repo

samuel@Sam MINGW64 ~/CV_RAMAN/first_repo (master)
$ touch README.md

samuel@Sam MINGW64 ~/CV_RAMAN/first_repo (master)
$ code README.md

samuel@Sam MINGW64 ~/CV_RAMAN/first_repo (master)
$ git push
error: src refspec refs/heads/master does not match any
error: failed to push some refs to 'https://github.com/samuel-kandukuri-au13/CV_RAMAN.git'

samuel@Sam MINGW64 ~/CV_RAMAN/first_repo (master)
$ cd..
bash: cd..: command not found

samuel@Sam MINGW64 ~/CV_RAMAN/first_repo (master)
$ cd..
bash: cd..: command not found

samuel@Sam MINGW64 ~/CV_RAMAN/first_repo (master)
$ git add .

samuel@Sam MINGW64 ~/CV_RAMAN/first_repo (master)
$ git commit -m "first_repo Demo"
[master (root-commit) 2e809c5] first_repo Demo
 1 file changed, 1 insertion(+)
 create mode 100644 README.md

samuel@Sam MINGW64 ~/CV_RAMAN/first_repo (master)
$ git push
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 235 bytes | 117.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/samuel-kandukuri-au13/CV_RAMAN.git
 * [new branch]      master -> master

samuel@Sam MINGW64 ~/CV_RAMAN/first_repo (master)
$ cd..
bash: cd..: command not found

samuel@Sam MINGW64 ~/CV_RAMAN/first_repo (master)
$ cd ..

samuel@Sam MINGW64 ~/CV_RAMAN (master)
$ git clone https://github.com/samuel-kandukuri-au13/CV_RAMAN.git second_repo
Cloning into 'second_repo'...
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 3 (delta 0), pack-reused 0
Unpacking objects: 100% (3/3), 215 bytes | 1024 bytes/s, done.

samuel@Sam MINGW64 ~/CV_RAMAN (master)
$ cd second_repo

samuel@Sam MINGW64 ~/CV_RAMAN/second_repo (master)
$ ls
README.md

samuel@Sam MINGW64 ~/CV_RAMAN/second_repo (master)
$ code README.md

samuel@Sam MINGW64 ~/CV_RAMAN/second_repo (master)
$ git add .

samuel@Sam MINGW64 ~/CV_RAMAN/second_repo (master)
$ git commit -m "second_repo Demo"
[master a7399d8] second_repo Demo
 1 file changed, 3 insertions(+), 1 deletion(-)

samuel@Sam MINGW64 ~/CV_RAMAN/second_repo (master)
$ git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 293 bytes | 293.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/samuel-kandukuri-au13/CV_RAMAN.git
   2e809c5..a7399d8  master -> master

samuel@Sam MINGW64 ~/CV_RAMAN/second_repo (master)
$ cd..
bash: cd..: command not found

samuel@Sam MINGW64 ~/CV_RAMAN/second_repo (master)
$ cd ..

samuel@Sam MINGW64 ~/CV_RAMAN (master)
$ cd first_repo

samuel@Sam MINGW64 ~/CV_RAMAN/first_repo (master)
$ git pull
remote: Enumerating objects: 5, done.
remote: Counting objects: 100% (5/5), done.
remote: Compressing objects: 100% (2/2), done.
remote: Total 3 (delta 0), reused 3 (delta 0), pack-reused 0
Unpacking objects: 100% (3/3), 273 bytes | 0 bytes/s, done.
From https://github.com/samuel-kandukuri-au13/CV_RAMAN
   2e809c5..a7399d8  master     -> origin/master
Updating 2e809c5..a7399d8
Fast-forward
 README.md | 4 +++-
 1 file changed, 3 insertions(+), 1 deletion(-)

samuel@Sam MINGW64 ~/CV_RAMAN/first_repo (master)
$ cd second_repo
bash: cd: second_repo: No such file or directory

samuel@Sam MINGW64 ~/CV_RAMAN/first_repo (master)
$ cd ..

samuel@Sam MINGW64 ~/CV_RAMAN (master)
$ cd second_repo

samuel@Sam MINGW64 ~/CV_RAMAN/second_repo (master)
$ code README.md

samuel@Sam MINGW64 ~/CV_RAMAN/second_repo (master)
$ git add .

samuel@Sam MINGW64 ~/CV_RAMAN/second_repo (master)
$ git commit -m "second_repo "
[master f0df269] second_repo
 1 file changed, 1 insertion(+), 1 deletion(-)

samuel@Sam MINGW64 ~/CV_RAMAN/second_repo (master)
$ cd ..

samuel@Sam MINGW64 ~/CV_RAMAN (master)
$ cd first_repo

samuel@Sam MINGW64 ~/CV_RAMAN/first_repo (master)
$ git pull
Already up to date.

samuel@Sam MINGW64 ~/CV_RAMAN/first_repo (master)
$
