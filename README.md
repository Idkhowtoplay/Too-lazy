## how to push ##
```
1.fork repo dulu ygy
2.git init
3.git clone link repo
4.cd dulu ke folder
5.code .
6.kerjakan bagianmu
7.git branch namabranch ytta
8.git switch namabranch
9.git add .
10.if file tidak ada cd dulu ke folder repo nya
11.git commit -m "aku sudah kerja"
12.git remote add origin link repo
13.git push -u origin nama branch
```
warning!!!! 
pastikan akun github nya sudah kamu ganti
jika nyangkut sama akun lain ke control panel terus search credential manager hapus akun github orang lain
gl gl yall

How to solve this problem of "! [rejected] master -> master (fetch first)"

First Do this ...

git fetch origin master
git merge  master

Then, do this ...

git fetch origin master:tmp
git rebase tmp
git push origin HEAD:master
git branch -D tmp

kalau yang error nya main yah ganti jadi main kocak
