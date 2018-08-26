# issues2
linuxlab37:~> cd ~
linuxlab37:~> mkdir cs110
mkdir: cannot create directory `cs110': File exists
linuxlab37:~> pwd
/u0/users/0/kcitlak1
linuxlab37:~> cd cs110
linuxlab37:~/cs110> pwd
/u0/users/0/kcitlak1/cs110
linuxlab37:~/cs110> cat commands.txt
 rm deletes everything from the folder, Is lists the files in the current working directory, mv moves one or more files to another 
linuxlab37:~/cs110> git clone https://github.com/binghamtonuniversity-cs110/lab-1-fall18-Korhan5
fatal: destination path 'lab-1-fall18-Korhan5' already exists and is not an empty directory.
linuxlab37:~/cs110> mkdir clone
linuxlab37:~/cs110> cd clone
linuxlab37:~/cs110/clone> gedit lab1.py &
[1] 9822
linuxlab37:~/cs110/clone> python3 lab1.py
python3: can't open file 'lab1.py': [Errno 2] No such file or directory
linuxlab37:~/cs110/clone> pwd
/u0/users/0/kcitlak1/cs110/clone
linuxlab37:~/cs110/clone> python3 lab1.py
python3: can't open file 'lab1.py': [Errno 2] No such file or directory
linuxlab37:~/cs110/clone> pyhton3 lab1.py
pyhton3: Command not found.
linuxlab37:~/cs110/clone> python3 lab1.py
Hello World
linuxlab37:~/cs110/clone> git commit -a -m "first commit"
fatal: Not a git repository (or any parent up to mount parent )
Stopping at filesystem boundary (GIT_DISCOVERY_ACROSS_FILESYSTEM not set).
linuxlab37:~/cs110/clone> cd git clone
cd: Too many arguments.
linuxlab37:~/cs110/clone> git commit -a -m "first commit"
fatal: Not a git repository (or any parent up to mount parent )
Stopping at filesystem boundary (GIT_DISCOVERY_ACROSS_FILESYSTEM not set).
linuxlab37:~/cs110/clone> git config --global user.name "Korhan Citlak"
linuxlab37:~/cs110/clone> git config --global user.email "kcitlak1@binghamton.edu"
linuxlab37:~/cs110/clone> cd cs110\
? 
cs110: No such file or directory.
linuxlab37:~/cs110/clone> cd cs110
cs110: No such file or directory.
linuxlab37:~/cs110/clone> pwd
/u0/users/0/kcitlak1/cs110/clone
linuxlab37:~/cs110/clone> git commit -a -m "first commit"
fatal: Not a git repository (or any parent up to mount parent )
Stopping at filesystem boundary (GIT_DISCOVERY_ACROSS_FILESYSTEM not set).
linuxlab37:~/cs110/clone> git clone def main():
Badly placed ()'s.
linuxlab37:~/cs110/clone>     print("Hello World")
Badly placed ()'s.
linuxlab37:~/cs110/clone> git clone https://github.com/binghamtonuniversity-cs110/lab-1-fall18-Korhan5
Cloning into 'lab-1-fall18-Korhan5'...
Username for 'https://github.com': korhan5
Password for 'https://korhan5@github.com': 
remote: Counting objects: 57, done.
remote: Compressing objects: 100% (37/37), done.
remote: Total 57 (delta 16), reused 57 (delta 16), pack-reused 0
Unpacking objects: 100% (57/57), done.
linuxlab37:~/cs110/clone> git commit -a -m "first commit"
fatal: Not a git repository (or any parent up to mount parent )
Stopping at filesystem boundary (GIT_DISCOVERY_ACROSS_FILESYSTEM not set).
linuxlab37:~/cs110/clone> git commit -a -m "first commit"
fatal: Not a git repository (or any parent up to mount parent )
Stopping at filesystem boundary (GIT_DISCOVERY_ACROSS_FILESYSTEM not set).
linuxlab37:~/cs110/clone> git clone https://github.com/binghamtonuniversity-cs110/lab-1-fall18-Korhan5.git
fatal: destination path 'lab-1-fall18-Korhan5' already exists and is not an empty directory.
linuxlab37:~/cs110/clone> pwd
/u0/users/0/kcitlak1/cs110/clone
linuxlab37:~/cs110/clone> git commit -a -m "first commit"
fatal: Not a git repository (or any parent up to mount parent )
Stopping at filesystem boundary (GIT_DISCOVERY_ACROSS_FILESYSTEM not set).
linuxlab37:~/cs110/clone> git clone https://github.com/binghamtonuniversity-cs110/lab-1-fall18-Korhan5.git
fatal: destination path 'lab-1-fall18-Korhan5' already exists and is not an empty directory.
linuxlab37:~/cs110/clone> 

