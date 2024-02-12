1. This Folder, "1", contains my answers to quiz 1.  
2. .md is an extension that stands for markdown language. We use .md extension because git recognizes markdown language.  
3. No, git doesn't track empty folders.  
4. Yes. 
5. .git is used to intialize a project.  
6. It changes the directory from the current directory to the preferred directory.  
7. It lists all the files in a directory along with the hidden files.  
8. It shows the current directory you are in.  
9. Three different areas are: 1. Working Directory, 2. Staging Area, 3. .git Repository. Working Directory is where the user creates/modifies a project file. 
       Staging Area is where the user, after modifying a file, adds the file to for later permanent committment to the repository.
       .git Repository, projects when permanently committed to this area become a part of this repository and cn be extracted as when the user wishes.  
10. VCS is a software that records changes to a file or set of files over time so that you can recall specific versions later.  
11. 6 benefits are: 
       1. Each client has a copy of the central database in their local storage device.
       2. Every clone of the central repository with each client is fully backed up and up to date. 
       3. If the central server crashes, none of the clients will face data loss since they all have a copy and this copy can be used to restore the central repository in the central server. 
       4. Collaborative work is easy. 
       5. Tracking minor developments is relatively easy. 
       6. Storage is efficiently used.  
12. Three classes are: 1. Local, 2. Centralized, 3. Distributed.  
13. GitHub is the central server where all the repositories are stored, Git is a software that connects users with the central hub i.e GitHub.  
14. git status shows the current status of the project.  
15. git push --all pushes all the user's committs from a local repository to a remote repository, to place them there permanently and to be able to share the same with other users.  
16. git pull is used to pull/extract the latest version of a project so that the user can work on it independently.  
17. Markdown is a language or a way to style text on a web.  
18. To make a text bold on markdown you should start and end the text with 2 asterisks; " ** insert text ** ".  
19. To make a text italic on markdown you should start and end the text with 1 asterisk; " * insert text* ".  
20. git init.  
21. "." this shows the current directory and ".." takes you to the previous directory.  
22.
    3. $ cd $ pwd  
    4. $ touch testdir  
    9. $ cat README.md
       This is a README.md file for the test git project of quiz1.
    10. $ git status
        On branch master

        No commits yet

        Untracked files:
           (use "git add <file>..." to include in what will be committed)
                  README.md
                  testdir

        nothing added to commit but untracked files present (use "git add" to track)
    11. $ git add --all
        warning: in the working copy of 'README.md', LF will be replaced by CRLF the next time Git touches it
        warning: in the working copy of 'testdir', LF will be replaced by CRLF the next time Git touches it  


        $ git commit -m "committing the test project for quiz 1"
        [master (root-commit) 3b12bae] committing the test project for quiz 1
        2 files changed, 2 insertions(+)
        create mode 100644 README.md
        create mode 100644 testdir
    12. $ git status
        On branch master
        nothing to commit, working tree clean
    13. By executing that command, I successfully deleting the test directory. -rf forcibly executes the command, ignoring all warnimg signs.

23. Absolute path is the entire path that you would take to access or enter a directory if you were starting from the home directory. 
       Relative path is the path you would take to access or enter a directory if you are in a directory that is not the home directory. 
       Relative path is more appropriate since the relative path stays the same on any platform unlike the absolute path.
24. 



 





  




