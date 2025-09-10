# Linux-Commands


## Aim:

To study the execution of various Linux operating system commands.

## Linux:

Linux is an open-source operating system. The kernel is the heart of Linux OS which
 
helps the communication between hardware and software. The main advantage of Linux was that programmers can use Linux kernel to design their own custom OS.

Linux Commands:
All basic and advanced tasks can be done by executing commands. The commands are executed on Linux terminal. Linux commands are case sensitive.


## Commands:

### 1)	ls Command

The ls command is used to display a list of content of a directory.

 Syntax: ls

![image](https://github.com/user-attachments/assets/515d3f10-a956-46cd-9abb-cc078c9b5a34)


### 2)	pwd Command

The pwd command is used to display the location of the current working directory.

Syntax: pwd

![image](https://github.com/user-attachments/assets/126560e9-81fb-4f48-b2d6-fc1c687d7923)

 
### 3)	mkdir Command

The mkdir command is used to create a new directory under any directory.

Syntax: mkdir <directory name>

![image](https://github.com/user-attachments/assets/faff0a46-f085-47e6-9c3e-17a0804c192c)


### 4)	rmdir Command

The rmdir command is used to delete a directory.

Syntax: rmdir <directory name>

![image](https://github.com/user-attachments/assets/645b7709-ac2a-4f69-8290-1dab26cb1654)


### 5)	cd Command

The cd command is used to change the current directory.

Syntax: cd <directory name>

![image](https://github.com/user-attachments/assets/11b9a3cd-93b0-4523-aaef-1b6ff79a7a72)


### 6)	cat Command

The cat command is a multi-purpose utility in the Linux system. It can be used to create a file, display content of the file, copy the content of one file to another file, and more.

Syntax: cat [OPTION]... [FILE]..

![image](https://github.com/user-attachments/assets/44647c5d-6f0b-47e3-ae58-68a255bbf50f)

 
### 7)	cp Command

The cp command is used to copy a file or directory.

Syntax: cp <existing file name> <new file name>

![image](https://github.com/user-attachments/assets/84a642ac-a208-42ec-b741-8401626414bb)



### 8)	gedit Command

The gedit is a general-purpose text editor. It can be used to create and edit all kinds of text files.

Syntax: gedit file_name

![image](https://github.com/user-attachments/assets/2165b336-4119-432e-aeb6-ea76f1725ff7)


### 9)	su Command

The su command provides administrative access to another user. In other words, it allows access of the Linux shell to another user.

Syntax: su <user name>

![image](https://github.com/user-attachments/assets/751f7f38-38f3-4046-8791-1604f6b27c0a)


### 10)	mv Command

The mv command is used to move a file or a directory form one location to another location.

Syntax: mv <file name> <directory path>

![image](https://github.com/user-attachments/assets/191aeba3-450c-49de-8248-e4e5265f28ca)

 
## 11)	rename Command

The rename command is used to rename files. It is useful for renaming a large group of files.

Syntax: rename 's/old-name/new-name/' files

![image](https://github.com/user-attachments/assets/04e837d0-09d5-4b7e-8d2f-0f0745566af9)


### 12)	head Command

The head command is used to display the content of a file. It displays the first 10 lines of a file.

Syntax: head <file name>

![image](https://github.com/user-attachments/assets/bdf4d996-0e44-4f5b-ada0-150c71cfb58a)


### 13)	tail Command

The tail command is similar to the head command. The difference between both commands is that it displays the last ten lines of the file content. It is useful for reading the error message.

Syntax: tail <file name>

![image](https://github.com/user-attachments/assets/d1abc737-da54-482a-8f3b-3208f5c0b6ec)

 
### 14)	id Command

The id command is used to display the user ID (UID) and group ID (GID).

Syntax: id

![image](https://github.com/user-attachments/assets/c4e63382-19b1-462f-a8fb-4ac1b106c186)


### 15)	grep Command

The grep is the most powerful and used filter in a Linux system. The 'grep' stands for "global regular expression print." It is useful for searching the content from a file. Generally, it is used with the pipe.

Syntax: command | grep <search word>

![image](https://github.com/user-attachments/assets/d5d05747-0644-4862-ba9c-9be4634eeb89)


### 16)	tr Command

The tr command is used to translate the file content like from lower case to upper case.

Syntax: command | tr <'old'> <'new'>

![image](https://github.com/user-attachments/assets/111a3959-d573-48a0-bbf6-52a5b4eb52a1)


### 17)	chmod Command

The chmod command is used to change the access mode of a file (i.e., read, write or execute)

Syntax: chmod<options><permissions><file_name>


![image](https://github.com/user-attachments/assets/0437e7d3-9399-47ba-8de0-af2c4f44674e)


### 18)	tar Command

The tar command is used for creating Archieve and extracting the archieve files.

Syntax: tar[options][archieve-file] [file to be archieved]
$ tar xvzf file.tar *.c

![image](https://github.com/user-attachments/assets/0faa99fa-f1ad-45f9-a95d-aeded05b2520)

 
### 19)	chown Command

The chown command is used to change ownership.

Syntax: chown owner_name file_name

![image](https://github.com/user-attachments/assets/e47392dd-f5bf-41c7-b95c-79245763ecc1)


### 20)	make Command

The make command is used for building and maintaining group of program.

Syntax: make [-f makefile][options]…….[targets]….

![image](https://github.com/user-attachments/assets/d330e936-84f4-4e94-a206-1659319727fa)

### 21)	ifconfig Command

The ifconfig command is used to configure kernel-resident network interface.

Syntax: ifconfig[options][interface]

![image](https://github.com/user-attachments/assets/0042ccf4-9647-4bb3-bcdd-3c9e169b3a0c)


### 22)	chmod 777 Command

The chmod 777 command gives read, write and execute permission to the owner, group and public.

Syntax: chmod 777 file_name
$chmod -R 777 /path/to/file/or/folder

 ![image](https://github.com/user-attachments/assets/9781ab44-ee9c-4416-ac6d-0e11be392364)

### 23)	host Command

The host command is used to display the IP address for a given domain name and vice versa. It performs the DNS lookups for the DNS Query.

Syntax: host <domain name> or <ip address>

![image](https://github.com/user-attachments/assets/f51d6c24-79c7-4fcc-a2d2-4c34b3b18a83)


### 24)	gzip Command

The gzip command is used to truncate the file size. It is a compressing tool. It replaces the original file by the compressed file having '.gz' extension.

Syntax: gzip <file1> <file2> <file3>..

![image](https://github.com/user-attachments/assets/0b474ac8-f2d6-4360-a753-8d897c72a68f)

### 25)	sort Command

The sort command is used to sort files in alphabetical order.

Syntax:sort <file name>

![image](https://github.com/user-attachments/assets/8f9dbc43-e32b-4b44-9f3d-bae35ba8b62b)

 
### 26)	cal Command

The cal command is used to display the current month's calendar with the current date highlighted.

Syntax: cal

![image](https://github.com/user-attachments/assets/8e6db122-78d3-4034-a339-04d623308630)


### 27)	clear Command

Linux clear command is used to clear the terminal screen.

Syntax: clear

![image](https://github.com/user-attachments/assets/bce65060-aeea-4469-89fa-8ea90cdb5d24)


![image](https://github.com/user-attachments/assets/fac6b965-9372-4742-b51a-6b8e34da9c4f)

### 28)	mail Command

The mail command is used to send emails from the command line.

Syntax: mail -s "Subject" <recipient address>

![image](https://github.com/user-attachments/assets/54599c39-b774-49b0-8046-ecb6334019dd)

 
### 29)	df Command

The df command is used to display the disk space used in the file system. It displays the output as in the number of used blocks, available blocks, and the mounted directory.

Syntax: df

![image](https://github.com/user-attachments/assets/316f4eac-e920-4843-8a48-924e9cfc4d47)


### 30)	find Command

The find command is used to find a particular file within a directory.

Syntax: find.-name”*.pdf”

![image](https://github.com/user-attachments/assets/106fcb32-447f-4c14-acc8-a0d72c2f40dd)

![image](https://github.com/user-attachments/assets/ab0b43b3-244d-46e1-ad0c-6288f04aebfd)





















## Result:

Thus, the execution of various Linux commands is executed successfully using Ubuntu OS.
