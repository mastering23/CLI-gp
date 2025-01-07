# TESTING GIT COMMANDS BY ENGEL NOEL B.N.
Important Git Commands
Basic Git Commands
Clone a repository
git clone <repository_url>

Check the status of your repository
git status

Add files to the staging area
git add <file_name>
git add . (to add all changes in the current directory)

Commit changes
git commit -m "Your commit message"

Push changes to the remote repository
git push origin <branch_name>

Pull changes from the remote repository
git pull origin <branch_name>

Check the commit history
git log

Create a new branch
git branch <new_branch_name>

Switch branches
git checkout <branch_name>

Merge branches
git merge <branch_name>

Delete a branch
git branch -d <branch_name>

Important Bash Commands
File & Directory Management
Create a new directory
mkdir <directory_name>

List files in a directory
ls

List files with detailed information
ls -l

Create an empty file
touch <file_name>

Move or rename files
mv <source> <destination>

Copy files
cp <source> <destination>

Remove files
rm <file_name>

Remove a directory
rmdir <directory_name>

Remove a directory and its contents
rm -r <directory_name>

File Viewing & Searching
View the content of a file
cat <file_name>

View a file with pagination
less <file_name>

Search for a string in a file
grep <pattern> <file_name>

Display the first lines of a file
head <file_name>

Display the last lines of a file
tail <file_name>

Permissions & Ownership
Change file permissions
chmod <permissions> <file_name>

Change file owner
chown <user>:<group> <file_name>

Process Management
List running processes
ps

Stop a process
kill <process_id>

Find processes by name
pgrep <process_name>

Networking
Check network connectivity
ping <host>

Display network information
ifconfig

Check open ports
netstat -tuln

System Information
Display disk space usage
df -h

Display memory usage
free -h

Display system information
uname -a

Display the current date and time
date