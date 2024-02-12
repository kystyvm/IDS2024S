This Folder, "1", contains my answers to quiz 1.  

$ cd  
$ pwd  
$ cat README.md
This is a README.md file for the test git project of quiz1.  
$ git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        README.md
        testdir

nothing added to commit but untracked files present (use "git add" to track)  

$ git add --all
warning: in the working copy of 'README.md', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'testdir', LF will be replaced by CRLF the next time Git touches it  


$ git commit -m "committing the test project for quiz 1"
[master (root-commit) 3b12bae] committing the test project for quiz 1
 2 files changed, 2 insertions(+)
 create mode 100644 README.md
 create mode 100644 testdir  
  




