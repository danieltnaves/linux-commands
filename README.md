# Most used Linux Commands

![command-line](https://cloud.githubusercontent.com/assets/1865566/19805495/45b4a7e8-9ceb-11e6-88f9-6ca1148418fd.jpg)

**List directory content**

`$ ls`

`$ l`

**List directory content, hidden files and executables**

`$ ls -a`

**List directory content**

`$ ls`

**List directory content (detailed)**

`$ ls -l`

`$ ll`

**Print name of current/working directory**

`$ pwd`

**Change directory**

`$ cd /etc`

`$ cd ~`

**Back to previous directory**

`$ cd -`

**Back one level directory**

`$ cd ..`

**Create directory**

`$ mkdir sample-directory`

**Create directory with subdirectory**

`$ mkdir -p sample-directory/sample-sub-directory`

**Delete directory or file**

`$ rm -r sample-directory`

**Rename file**

`$ mv file.txt new-file.txt`

**Move file to destination**

`$ mv file.txt ~/Documents`

**Copy file to destination**

`$ cp file.txt ~/Documents`

**Create symlink  (i.e., create symlink at /opt/foo which references to file /usr/bin/bar)**

`$ ln -s /usr/bin/bar /opt/foo `

**Search for an executable path**

`$ type exec-name`

**Creates a new file**

`$ cat > file.txt`

`$ touch file.txt`

**Compares two files**

`$ diff file1.txt file2.txt`

**Locates a file**

`$ locate file.txt`

**Shows file lines starting from the beginning**

`$ head -20 file.txt`

**Shows file lines starting from end**

`$ tail -20 file.txt`

**Output appended data as the file grows**

`$ tail -f file.txt`

**Shows file content (scrolling)**

`$ less file.txt`

**Shows file content (scrolling)**

`$ more file.txt`

**Shows file lines number**

`$ nl file.txt`

**List last used commands**

`$ history`

**Change to super user mode**

`$ su`

**Execute command as super user**

`$ sudo vi /etc/enviroment`

**Shutdown machine**

`$ shutdown`

`$ halt`

**Reboot machine**

`$ reboot`

**Change user password**

`$ passwd`

**Show SO, machine name, version, kernel version, date and architecture**

`$ uname -a`

**Show process information**

`$ top`

**List process information**

`$ ps aux`

`$ ps aux | grep process-name`

**Find PID number**

`$ pidof firefox`

**Find out process name using PID number**

`$ ps -p 2523 -o comm=`

**Kills a process by name**

`$ killall -9 process-name`

**Kills a process greping strings**

`$ pkill -9 -f jboss`

**Changes the mouse pointer in a process killer**

`$ xkill`

**Shows machine architecture**

`$ arch`

**Add user to OS**

`$ adduser dummy`

**Remove user from OS**

`$ userdel dummy`

**Remove user and home directory contents**

`$ userdel -r dummy`

**Displays an image (requires ImageMagick)**

`$ display image.jpg`

**Convert image format (requires ImageMagick)**

`$ converte image.jpg image.png`

**Change permissions**

`$ chmod 666 ~/directory`

**Mounts a device**

`$ mount /mnt/cdrom`

**Unmounts a device**

`$ unmount /mnt/cdrom`

**Show date and hour**

`$ date`

**Starts a process in background and leaves terminal ready to do another work**

`$ mvn package &`

**Show calender**

`$ cal`

**Clear screen**

`$ clear`

**Show RAM information**

`$ free`


**Measure program start time**

`$ time subl`


**List file attributes**

`$ lsattr file.txt`


**Find executable path**

`$ whereis exec-name`


**Download file**

`$ wget -c http://www.xpto.com/file.txt`
