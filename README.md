# clone repository
* step1: 进入https://github.com/charlottelch/giftshop 点击 clone or download复制这个地址。
* step2: 
```
C:\Users\ASUS>cd c:\

c:\>git clone https://github.com/charlottelch/giftshop.git
Cloning into 'giftshop'...
remote: Counting objects: 3, done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (3/3), done.
```




# upload webpage to github
Example: upload c:\   to https://github.com/charlottelch/charlottelch.github.io/tree/master/webdesign
* step 1:ctrl c ,ctrl v from C:\Users\ASUS\Desktop\网页设计作业\第8章614李长虹\抒情散文网 to C:\charlottelch.github.io\webdesign\essay
* step 2: git status
```
c:\charlottelch.github.io>git status
On branch master
Your branch is up-to-date with 'origin/master'.
Untracked files:
  (use "git add <file>..." to include in what will be committed)

        webdesign/essay/

nothing added to commit but untracked files present (use "git add" to track)
```
* step 3:
```
c:\charlottelch.github.io>git add webdesign/essay
```
* step 4:
```
c:\charlottelch.github.io>git status
On branch master
Your branch is up-to-date with 'origin/master'.
Changes to be committed:
  (use "git reset HEAD <file>..." to unstage)

        new file:   webdesign/essay/images/a_01.jpg
        new file:   webdesign/essay/images/a_02.jpg
        new file:   webdesign/essay/images/a_03.jpg
        new file:   webdesign/essay/images/a_04.jpg
        new file:   webdesign/essay/images/a_05.jpg
        new file:   webdesign/essay/images/b_06.gif
        new file:   webdesign/essay/index.html
```
* step 5:
```
c:\charlottelch.github.io>git commit -m "webdesign/essay"
[master 920134f] webdesign/essay
 7 files changed, 32 insertions(+)
 create mode 100644 webdesign/essay/images/a_01.jpg
 create mode 100644 webdesign/essay/images/a_02.jpg
 create mode 100644 webdesign/essay/images/a_03.jpg
 create mode 100644 webdesign/essay/images/a_04.jpg
 create mode 100644 webdesign/essay/images/a_05.jpg
 create mode 100644 webdesign/essay/images/b_06.gif
 create mode 100644 webdesign/essay/index.html
 ```
 * step 6:
 ```
 c:\charlottelch.github.io>git status
On branch master
Your branch is ahead of 'origin/master' by 1 commit.
  (use "git push" to publish your local commits)
nothing to commit, working tree clean

c:\charlottelch.github.io>git push
To https://github.com/charlottelch/charlottelch.github.io
 ! [rejected]        master -> master (fetch first)
error: failed to push some refs to 'https://github.com/charlottelch/charlottelch.github.io'
hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

c:\charlottelch.github.io>git pull (because we changed index2.html to index.html by the web interface)
remote: Counting objects: 5, done.
remote: Compressing objects: 100% (5/5), done.
remote: Total 5 (delta 2), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (5/5), done.
From https://github.com/charlottelch/charlottelch.github.io
   a7880db..4b7b307  master     -> origin/master
Auto-merging webdesign/gift/index.html
Merge made by the 'recursive' strategy.
 webdesign/gift/{index2.html => index.html} | 4 ++--
 1 file changed, 2 insertions(+), 2 deletions(-)
 rename webdesign/gift/{index2.html => index.html} (98%)

c:\charlottelch.github.io>git push
Counting objects: 15, done.
Delta compression using up to 4 threads.
Compressing objects: 100% (15/15), done.
Writing objects: 100% (15/15), 113.05 KiB | 0 bytes/s, done.
Total 15 (delta 4), reused 0 (delta 0)
remote: Resolving deltas: 100% (4/4), completed with 2 local objects.
To https://github.com/charlottelch/charlottelch.github.io
   4b7b307..e9ff014  master -> master
```
# level1
## level2

# level 1
## level2
## level 2
### level 3
