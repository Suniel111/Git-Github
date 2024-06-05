# Git-Github

Learning Git &amp; Github from scratch

to clone a repo use command
git clone <HTTPS link of github repo>

# status --> command shows the status of a repo

git status

to add modification of a file use the command add & will have to commit to see on the repo
git add -----> to add file, it add new or modified files
git commit --------> to upload the file into server

# types of file

4 types of files

1. untracked file -> new file that has not been added nor commited to the server
2. modified -> the file has already present in the server but some modification has been done and not added as well as commited to the server
3. staged -> the file is added but not commited so, it will not show in the server
4. unmodified -> no changes has been done in the file

# git push command -> upload local repo content to remote repo

this is last command to upload the file in the server

# Steps to upload files from local to pre build github repo

1. Copy the repo link
2. run command "git clone <link>"
3. Build your projects and create files
4. after completing project to add all files in the git repo run command "git add ."
5. run command "git commit -m 'your message(compulsary)'"
6. to add file in main branch run command "git push origin main"
