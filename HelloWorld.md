Last login: Fri Jan 20 13:44:54 on ttys001
jessicas-mbp-2:Data_Analysis jessicamesquita$ git add -A
jessicas-mbp-2:Data_Analysis jessicamesquita$ git commit -m "added subtitle"
On branch master
Changes not staged for commit:
	modified:   Data_Analysis (untracked content)

no changes added to commit
jessicas-mbp-2:Data_Analysis jessicamesquita$ 
  [Restored 20 Jan 17 14:01:46]
Last login: Fri Jan 20 13:47:00 on ttys002
Restored session: Fri Jan 20 14:01:34 CET 2017
jessicas-mbp-2:Data_Analysis jessicamesquita$ cd ~/Documents/Courses/Data Science/ Toolbox
-bash: cd: /Users/jessicamesquita/Documents/Courses/Data: No such file or directory
jessicas-mbp-2:Data_Analysis jessicamesquita$ cd ~/Documents
jessicas-mbp-2:Documents jessicamesquita$ ~/Documents/Courses
-bash: /Users/jessicamesquita/Documents/Courses: is a directory
jessicas-mbp-2:Documents jessicamesquita$ cd ~/Documents/Courses
jessicas-mbp-2:Courses jessicamesquita$ cd ~/Documents/Courses/Data_Science
-bash: cd: /Users/jessicamesquita/Documents/Courses/Data_Science: No such file or directory
jessicas-mbp-2:Courses jessicamesquita$ cd ~/Documents/Courses/DataScience
-bash: cd: /Users/jessicamesquita/Documents/Courses/DataScience: No such file or directory
jessicas-mbp-2:Courses jessicamesquita$ cd ~/Documents/Courses/Data Science
-bash: cd: /Users/jessicamesquita/Documents/Courses/Data: No such file or directory
jessicas-mbp-2:Courses jessicamesquita$ cd ~/Documents/Courses/Data 
-bash: cd: /Users/jessicamesquita/Documents/Courses/Data: No such file or directory
jessicas-mbp-2:Courses jessicamesquita$ cd ~/Documents/Courses/Data_Science
jessicas-mbp-2:Data_Science jessicamesquita$ cd ~/Documents/Courses/Data_Science/Toolbox
jessicas-mbp-2:Toolbox jessicamesquita$ cd ~/Documents/Courses/Data_Science/To_Commit
jessicas-mbp-2:To_Commit jessicamesquita$ git init
Initialized empty Git repository in /Users/jessicamesquita/Documents/Courses/Data_Science/To_Commit/.git/
jessicas-mbp-2:To_Commit jessicamesquita$ git add -A
jessicas-mbp-2:To_Commit jessicamesquita$ git commit -m "initial commit"
[master (root-commit) f0cd53c] initial commit
 2 files changed, 202 insertions(+)
 create mode 100644 HelloWorld.md
 create mode 100644 Terminal Saved Output
jessicas-mbp-2:To_Commit jessicamesquita$ git -A
Unknown option: -A
usage: git [--version] [--help] [-C <path>] [-c name=value]
           [--exec-path[=<path>]] [--html-path] [--man-path] [--info-path]
           [-p | --paginate | --no-pager] [--no-replace-objects] [--bare]
           [--git-dir=<path>] [--work-tree=<path>] [--namespace=<name>]
           <command> [<args>]
jessicas-mbp-2:To_Commit jessicamesquita$ git add -A
jessicas-mbp-2:To_Commit jessicamesquita$ git commit -m "initial commit"
[master 84f2fdd] initial commit
 2 files changed, 12 insertions(+), 202 deletions(-)
 rewrite HelloWorld.md (98%)
 delete mode 100644 Terminal Saved Output
jessicas-mbp-2:To_Commit jessicamesquita$ git status
On branch master
nothing to commit, working tree clean
jessicas-mbp-2:To_Commit jessicamesquita$ git show
commit 84f2fdd4b5b7081b34aeea3866a0044e6a698d68
Author: JesbeirBioHacks <mesquita.jessica.f@gmail.com>
Date:   Fri Jan 20 14:16:36 2017 +0100

    initial commit

diff --git a/HelloWorld.md b/HelloWorld.md
index 5040076..96872f7 100644
--- a/HelloWorld.md
+++ b/HelloWorld.md
@@ -1,76 +1,3 @@
-Last login: Tue Jan 17 13:50:45 on ttys000
-192:~ jessicamesquita$ 
-  [Restored 17 Jan 17 13:56:11]
-Last login: Tue Jan 17 13:50:57 on ttys001
-Restored session: Tue Jan 17 13:56:05 CET 2017
-192:~ jessicamesquita$ cd ~/Data_Analysis
-192:Data_Analysis jessicamesquita$ git init
-Reinitialized existing Git repository in /Users/jessicamesquita/Data_Analysis/.git/
-192:Data_Analysis jessicamesquita$ git show
-commit 5a9805464a91c7a23c85fa69eb8b9843d241d7f0
-Author: JesbeirBioHacks <mesquita.jessica.f@gmail.com>
-Date:   Tue Jan 17 13:59:19 2017 +0100
-
-    second attempt to commit
-
-diff --git a/Data_Analysis b/Data_Analysis
-new file mode 160000
-index 0000000..b0f73f7
---- /dev/null
-+++ b/Data_Analysis
-commit 5a9805464a91c7a23c85fa69eb8b9843d241d7f0
-Author: JesbeirBioHacks <mesquita.jessica.f@gmail.com>
-Date:   Tue Jan 17 13:59:19 2017 +0100
-
-    second attempt to commit
-
-diff --git a/Data_Analysis b/Data_Analysis
-new file mode 160000
-index 0000000..b0f73f7
---- /dev/null
-+++ b/Data_Analysis
-@@ -0,0 +1 @@
-+Subproject commit b0f73f7793886c486755d68fa822ee3aa853fbad
-diff --git a/JesbeirBioHacks.github.io b/JesbeirBioHacks.github.io
-new file mode 160000
-index 0000000..12d5205
---- /dev/null
-+++ b/JesbeirBioHacks.github.io
-@@ -0,0 +1 @@
-+Subproject commit 12d5205c63fba800ac59bee8ba507e04f32cde5c
-diff --git a/nano.save b/nano.save
-new file mode 100644
-index 0000000..d90d593
---- /dev/null
-:
-  [Restored 17 Jan 17 14:04:24]
-Last login: Tue Jan 17 13:56:11 on ttys000
-Restored session: Tue Jan 17 14:04:20 CET 2017
-192:Data_Analysis jessicamesquita$ git init
-Reinitialized existing Git repository in /Users/jessicamesquita/Data_Analysis/.git/
-192:Data_Analysis jessicamesquita$ git push
-fatal: The current branch master has no upstream branch.
-To push the current branch and set the remote as upstream, use
-
-    git push --set-upstream origin master
-
-192:Data_Analysis jessicamesquita$ git push --set-upstream origin master
-remote: Repository not found.
-fatal: repository 'https://github.com/JesbeirBioHacks/Data_Analyis.git/' not found
-192:Data_Analysis jessicamesquita$ git 
-  [Restored 20 Jan 17 13:35:11]
-Last login: Tue Jan 17 23:05:42 on console
-jessicas-mbp-2:Data_Analysis jessicamesquita$ touch HelloWorld.md
-jessicas-mbp-2:Data_Analysis jessicamesquita$ pwd
-/Users/jessicamesquita/Data_Analysis
-jessicas-mbp-2:Data_Analysis jessicamesquita$ git add .
-jessicas-mbp-2:Data_Analysis jessicamesquita$ git commit -m "initial commit"
-[master bf1ccc6] initial commit
- 1 file changed, 0 insertions(+), 0 deletions(-)
- create mode 100644 HelloWorld.md
-jessicas-mbp-2:Data_Analysis jessicamesquita$ nano HelloWorld.md
-
-  GNU nano 2.0.6             File: HelloWorld.md                      Modified  
 
 ##This is a markdown file
 
@@ -83,14 +10,3 @@ jessicas-mbp-2:Data_Analysis jessicamesquita$ nano HelloWorld.md
 
 
 
-
-
-
-
-
-
-
-
-
-^G Get Help  ^O WriteOut  ^R Read File ^Y Prev Page ^K Cut Text  ^C Cur Pos
-^X Exit      ^J Justify   ^W Where Is  ^V Next Page ^U UnCut Text^T To Spell
diff --git a/Terminal Saved Output b/Terminal Saved Output
deleted file mode 100644
index 620ea84..0000000
--- a/Terminal Saved Output     
+++ /dev/null
@@ -1,106 +0,0 @@
-Last login: Tue Jan 17 13:50:45 on ttys000
-192:~ jessicamesquita$ 
-  [Restored 17 Jan 17 13:56:11]
-Last login: Tue Jan 17 13:50:57 on ttys001
-Restored session: Tue Jan 17 13:56:05 CET 2017
-192:~ jessicamesquita$ cd ~/Data_Analysis
-192:Data_Analysis jessicamesquita$ git init
-Reinitialized existing Git repository in /Users/jessicamesquita/Data_Analysis/.git/
-192:Data_Analysis jessicamesquita$ git show
-commit 5a9805464a91c7a23c85fa69eb8b9843d241d7f0
-Author: JesbeirBioHacks <mesquita.jessica.f@gmail.com>
-Date:   Tue Jan 17 13:59:19 2017 +0100
-
-    second attempt to commit
-
-diff --git a/Data_Analysis b/Data_Analysis
-new file mode 160000
-index 0000000..b0f73f7
---- /dev/null
-+++ b/Data_Analysis
-commit 5a9805464a91c7a23c85fa69eb8b9843d241d7f0
-Author: JesbeirBioHacks <mesquita.jessica.f@gmail.com>
-Date:   Tue Jan 17 13:59:19 2017 +0100
-
-    second attempt to commit
-
-diff --git a/Data_Analysis b/Data_Analysis
-new file mode 160000
-index 0000000..b0f73f7
---- /dev/null
-+++ b/Data_Analysis
-@@ -0,0 +1 @@
-+Subproject commit b0f73f7793886c486755d68fa822ee3aa853fbad
-diff --git a/JesbeirBioHacks.github.io b/JesbeirBioHacks.github.io
-new file mode 160000
-index 0000000..12d5205
---- /dev/null
-+++ b/JesbeirBioHacks.github.io
-@@ -0,0 +1 @@
-+Subproject commit 12d5205c63fba800ac59bee8ba507e04f32cde5c
-diff --git a/nano.save b/nano.save
-new file mode 100644
-index 0000000..d90d593
---- /dev/null
-:
-  [Restored 17 Jan 17 14:04:24]
-Last login: Tue Jan 17 13:56:11 on ttys000
-Restored session: Tue Jan 17 14:04:20 CET 2017
-192:Data_Analysis jessicamesquita$ git init
-Reinitialized existing Git repository in /Users/jessicamesquita/Data_Analysis/.git/
-192:Data_Analysis jessicamesquita$ git push
-fatal: The current branch master has no upstream branch.
-To push the current branch and set the remote as upstream, use
-
-    git push --set-upstream origin master
-
-192:Data_Analysis jessicamesquita$ git push --set-upstream origin master
-remote: Repository not found.
-fatal: repository 'https://github.com/JesbeirBioHacks/Data_Analyis.git/' not found
-192:Data_Analysis jessicamesquita$ git 
-  [Restored 20 Jan 17 13:35:11]
-Last login: Tue Jan 17 23:05:42 on console
-jessicas-mbp-2:Data_Analysis jessicamesquita$ touch HelloWorld.md
-jessicas-mbp-2:Data_Analysis jessicamesquita$ pwd
-/Users/jessicamesquita/Data_Analysis
-jessicas-mbp-2:Data_Analysis jessicamesquita$ git add .
-jessicas-mbp-2:Data_Analysis jessicamesquita$ git commit -m "initial commit"
-[master bf1ccc6] initial commit
- 1 file changed, 0 insertions(+), 0 deletions(-)
- create mode 100644 HelloWorld.md
-jessicas-mbp-2:Data_Analysis jessicamesquita$ nano HelloWorld.md
-
-  [Restored 20 Jan 17 14:01:46]
-Last login: Fri Jan 20 13:47:00 on ttys002
-Restored session: Fri Jan 20 14:01:34 CET 2017
-jessicas-mbp-2:Data_Analysis jessicamesquita$ git add -A
-jessicas-mbp-2:Data_Analysis jessicamesquita$ git commit -m "subtitle updated"
-[master dcfcc45] subtitle updated
- 1 file changed, 2 insertions(+)
- create mode 100644 HelloWorld.md.save
-jessicas-mbp-2:Data_Analysis jessicamesquita$ nano HelloWorld.md
-
-  GNU nano 2.0.6             File: HelloWorld.md                      Modified  
-
-## This is a markdwon file
-
-
-
-
-
-
-
-
-
-
-
-
-
-
-
-
-
-
-
-^G Get Help  ^O WriteOut  ^R Read File ^Y Prev Page ^K Cut Text  ^C Cur Pos
-^X Exit      ^J Justify   ^W Where Is  ^V Next Page ^U UnCut Text^T To Spell
(END)
  [Restored 20 Jan 17 14:19:51]
Last login: Fri Jan 20 14:01:46 on ttys002
Restored session: Fri Jan 20 14:19:47 CET 2017
jessicas-mbp-2:To_Commit jessicamesquita$ git push
fatal: No configured push destination.
Either specify the URL from the command-line or configure a remote repository using

    git remote add <name> <url>

and then push using the remote name

    git push <name>

jessicas-mbp-2:To_Commit jessicamesquita$ git remote https://github.com/JesbeirBioHacks/DataScienceCoursera.git
error: Unknown subcommand: https://github.com/JesbeirBioHacks/DataScienceCoursera.git
usage: git remote [-v | --verbose]
   or: git remote add [-t <branch>] [-m <master>] [-f] [--tags | --no-tags] [--mirror=<fetch|push>] <name> <url>
   or: git remote rename <old> <new>
   or: git remote remove <name>
   or: git remote set-head <name> (-a | --auto | -d | --delete | <branch>)
   or: git remote [-v | --verbose] show [-n] <name>
   or: git remote prune [-n | --dry-run] <name>
   or: git remote [-v | --verbose] update [-p | --prune] [(<group> | <remote>)...]
   or: git remote set-branches [--add] <name> <branch>...
   or: git remote get-url [--push] [--all] <name>
   or: git remote set-url [--push] <name> <newurl> [<oldurl>]
   or: git remote set-url --add <name> <newurl>
   or: git remote set-url --delete <name> <url>

    -v, --verbose         be verbose; must be placed before a subcommand

jessicas-mbp-2:To_Commit jessicamesquita$ git remote add https://github.com/JesbeirBioHacks/DataScienceCoursera.git
usage: git remote add [<options>] <name> <url>

    -f, --fetch           fetch the remote branches
    --tags                import all tags and associated objects when fetching
                          or do not fetch any tag at all (--no-tags)
    -t, --track <branch>  branch(es) to track
    -m, --master <branch>
                          master branch
    --mirror[=<push|fetch>]
                          set up remote as a mirror to push to or fetch from

jessicas-mbp-2:To_Commit jessicamesquita$ git remote add origin  https://github.com/JesbeirBioHacks/DataScienceCoursera.git
jessicas-mbp-2:To_Commit jessicamesquita$ git push origin master
To https://github.com/JesbeirBioHacks/DataScienceCoursera.git
 ! [rejected]        master -> master (fetch first)
error: failed to push some refs to 'https://github.com/JesbeirBioHacks/DataScienceCoursera.git'
hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.
jessicas-mbp-2:To_Commit jessicamesquita$ git pull origin master
warning: no common commits
remote: Counting objects: 3, done.
remote: Compressing objects: 100% (2/2), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (3/3), done.
From https://github.com/JesbeirBioHacks/DataScienceCoursera
 * branch            master     -> FETCH_HEAD
 * [new branch]      master     -> origin/master
fatal: refusing to merge unrelated histories
jessicas-mbp-2:To_Commit jessicamesquita$ git clone https://github.com/JesbeirBioHacks/DataScienceCoursera.git
Cloning into 'DataScienceCoursera'...
remote: Counting objects: 3, done.
remote: Compressing objects: 100% (2/2), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (3/3), done.
jessicas-mbp-2:To_Commit jessicamesquita$ git add -A
jessicas-mbp-2:To_Commit jessicamesquita$ git commit -m "second attempt"
[master 31bfdbb] second attempt
 1 file changed, 1 insertion(+)
 create mode 160000 DataScienceCoursera
jessicas-mbp-2:To_Commit jessicamesquita$ touch HelloWorld.md
jessicas-mbp-2:To_Commit jessicamesquita$ git add -A
jessicas-mbp-2:To_Commit jessicamesquita$ git commit -m "third attempt"
On branch master
nothing to commit, working tree clean
jessicas-mbp-2:To_Commit jessicamesquita$ git push origin master
To https://github.com/JesbeirBioHacks/DataScienceCoursera.git
 ! [rejected]        master -> master (non-fast-forward)
error: failed to push some refs to 'https://github.com/JesbeirBioHacks/DataScienceCoursera.git'
hint: Updates were rejected because the tip of your current branch is behind
hint: its remote counterpart. Integrate the remote changes (e.g.
hint: 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.
jessicas-mbp-2:To_Commit jessicamesquita$ git push --help

  [Restored 20 Jan 17 14:35:11]
Last login: Fri Jan 20 14:19:51 on ttys002
Restored session: Fri Jan 20 14:35:08 CET 2017
jessicas-mbp-2:To_Commit jessicamesquita$ git push --force
fatal: The current branch master has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin master

jessicas-mbp-2:To_Commit jessicamesquita$ git push --set-upstream origin master
To https://github.com/JesbeirBioHacks/DataScienceCoursera.git
 ! [rejected]        master -> master (non-fast-forward)
error: failed to push some refs to 'https://github.com/JesbeirBioHacks/DataScienceCoursera.git'
hint: Updates were rejected because the tip of your current branch is behind
hint: its remote counterpart. Integrate the remote changes (e.g.
hint: 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.
jessicas-mbp-2:To_Commit jessicamesquita$ git pull origin master
From https://github.com/JesbeirBioHacks/DataScienceCoursera
 * branch            master     -> FETCH_HEAD
fatal: refusing to merge unrelated histories
jessicas-mbp-2:To_Commit jessicamesquita$ git status
On branch master
nothing to commit, working tree clean
jessicas-mbp-2:To_Commit jessicamesquita$ git show
commit 31bfdbb257d522103c41b28f795ae92cd83d3821
Author: JesbeirBioHacks <mesquita.jessica.f@gmail.com>
Date:   Fri Jan 20 14:25:21 2017 +0100

    second attempt

diff --git a/DataScienceCoursera b/DataScienceCoursera
new file mode 160000
index 0000000..e31858f
--- /dev/null
+++ b/DataScienceCoursera
@@ -0,0 +1 @@
+Subproject commit e31858ff8cbc264d44663fccc5413fefca32df4a
jessicas-mbp-2:To_Commit jessicamesquita$ touch HelloWorld.md
jessicas-mbp-2:To_Commit jessicamesquita$ git add -A
jessicas-mbp-2:To_Commit jessicamesquita$ git commit -m "second commit"
On branch master
nothing to commit, working tree clean
jessicas-mbp-2:To_Commit jessicamesquita$ git show
commit 31bfdbb257d522103c41b28f795ae92cd83d3821
Author: JesbeirBioHacks <mesquita.jessica.f@gmail.com>
Date:   Fri Jan 20 14:25:21 2017 +0100

    second attempt

diff --git a/DataScienceCoursera b/DataScienceCoursera
new file mode 160000
index 0000000..e31858f
--- /dev/null
+++ b/DataScienceCoursera
@@ -0,0 +1 @@
+Subproject commit e31858ff8cbc264d44663fccc5413fefca32df4a
jessicas-mbp-2:To_Commit jessicamesquita$ nano HelloWorld.md

  GNU nano 2.0.6             File: HelloWorld.md                      Modified  

##This is a markdown file



















^G Get Help  ^O WriteOut  ^R Read File ^Y Prev Page ^K Cut Text  ^C Cur Pos
^X Exit      ^J Justify   ^W Where Is  ^V Next Page ^U UnCut Text^T To Spell
