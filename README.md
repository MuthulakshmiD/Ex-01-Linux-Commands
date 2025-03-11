# Ex-01-Linux-Commands

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

![Screenshot 2025-03-11 133046](https://github.com/user-attachments/assets/7cac3d03-02a3-4444-9826-cc3deaf7c2e3)

### 2)	pwd Command

The pwd command is used to display the location of the current working directory.

Syntax: pwd

![Screenshot 2025-03-11 133223](https://github.com/user-attachments/assets/653bf36e-433f-4cbf-ae6c-28d64f00758f)

 
### 3)	mkdir Command

The mkdir command is used to create a new directory under any directory.

Syntax:
 mkdir <directory name>
 
![Screenshot 2025-03-11 133305](https://github.com/user-attachments/assets/9e9b4699-5a6a-4039-98b2-135a2fb1c22e)

### 4)	rmdir Command

The rmdir command is used to delete a directory.

Syntax: rmdir <directory name>

![Screenshot 2025-03-11 133320](https://github.com/user-attachments/assets/993c8784-4e8a-4a26-a58a-439abe178505)


### 5)	cd Command

The cd command is used to change the current directory.

Syntax: cd <directory name>

![Screenshot 2025-03-11 133342](https://github.com/user-attachments/assets/4b502858-4f71-43cc-9d4e-58407c59ab2d)


### 6)	cat Command

The cat command is a multi-purpose utility in the Linux system. It can be used to create a file, display content of the file, copy the content of one file to another file, and more.

Syntax: cat [OPTION]... [FILE]..

![Screenshot 2025-03-11 134517](https://github.com/user-attachments/assets/648900bb-517c-41de-aa41-3559c881260d)

 
### 7)	cp Command

The cp command is used to copy a file or directory.

Syntax: cp <existing file name> <new file name>

![Screenshot 2025-03-11 134531](https://github.com/user-attachments/assets/8f5e1930-28a6-4467-9bef-371d36f0f323)



### 8)	gedit Command

The gedit is a general-purpose text editor. It can be used to create and edit all kinds of text files.

Syntax: gedit file_name

![Screenshot 2025-03-11 134556](https://github.com/user-attachments/assets/47cdb9d8-7867-4a4b-a6e5-d3f38b00f456)


### 9)	su Command

The su command provides administrative access to another user. In other words, it allows access of the Linux shell to another user.

Syntax: su <user name>

![Screenshot 2025-03-11 134612](https://github.com/user-attachments/assets/ffa267a5-242f-42d2-b008-cf3665d1cae0)


### 10)	mv Command

The mv command is used to move a file or a directory form one location to another location.

Syntax: mv <file name> <directory path>

![Screenshot 2025-03-11 134621](https://github.com/user-attachments/assets/b88f4d0e-f58c-46ed-beaa-4135b09705b1)

 
## 11)	rename Command

The rename command is used to rename files. It is useful for renaming a large group of files.

Syntax: rename 's/old-name/new-name/' files

![Screenshot 2025-03-11 134632](https://github.com/user-attachments/assets/e9d724ee-26f0-4e16-955d-73d873a350eb)


### 12)	head Command

The head command is used to display the content of a file. It displays the first 10 lines of a file.

Syntax: head <file name>

![Screenshot 2025-03-11 134640](https://github.com/user-attachments/assets/de7b3f3e-2296-4fdb-9127-1c90b17f5392)


### 13)	tail Command

The tail command is similar to the head command. The difference between both commands is that it displays the last ten lines of the file content. It is useful for reading the error message.

Syntax: tail <file name>

![Screenshot 2025-03-11 134653](https://github.com/user-attachments/assets/3e08684f-af2e-4f94-8a63-753083fea8c5)

 
### 14)	id Command

The id command is used to display the user ID (UID) and group ID (GID).

Syntax: id

![Screenshot 2025-03-11 134702](https://github.com/user-attachments/assets/d9e63c05-0cae-4349-9cd5-53bb14767f8d)


### 15)	grep Command

The grep is the most powerful and used filter in a Linux system. The 'grep' stands for "global regular expression print." It is useful for searching the content from a file. Generally, it is used with the pipe.

Syntax: command | grep <search word>

![Screenshot 2025-03-11 134723](https://github.com/user-attachments/assets/01b9fb6c-9c9f-4681-a940-39fc8ccd85f3)


### 16)	tr Command

The tr command is used to translate the file content like from lower case to upper case.

Syntax: command | tr <'old'> <'new'>

![Screenshot 2025-03-11 134736](https://github.com/user-attachments/assets/0919b9bc-ef6a-4346-b2da-e1caca8186d4)



### 17)	chmod Command

The chmod command is used to change the access mode of a file (i.e., read, write or execute)

Syntax: chmod<options><permissions><file_name>

### 18)	tar Command

The tar command is used for creating Archieve and extracting the archieve files.

Syntax: tar[options][archieve-file] [file to be archieved]
$ tar xvzf file.tar *.c
 
### 19)	chown Command

The chown command is used to change ownership.

Syntax: chown owner_name file_name

![Screenshot 2025-03-11 134751](https://github.com/user-attachments/assets/71d6872e-03c6-4be3-ba6f-c2e9340cfe39)



### 20)	make Command

The make command is used for building and maintaining group of program.

Syntax: make [-f makefile][options]…….[targets]….

![Screenshot 2025-03-11 134926](https://github.com/user-attachments/assets/c20bec99-7723-4dcf-9167-622944614146)



### 21)	ifconfig Command

The ifconfig command is used to configure kernel-resident network interface.

Syntax: ifconfig[options][interface]
![Screenshot 2025-03-11 135616](https://github.com/user-attachments/assets/fab696e8-3d91-433d-9c8c-8fa6094b7b9b)




### 22)	chmod 777 Command

The chmod 777 command gives read, write and execute permission to the owner, group and public.

Syntax: chmod 777 file_name
$chmod -R 777 /path/to/file/or/folder
 
### 23)	host Command

The host command is used to display the IP address for a given domain name and vice versa. It performs the DNS lookups for the DNS Query.

Syntax: host <domain name> or <ip address>

![Screenshot 2025-03-11 135058](https://github.com/user-attachments/assets/d9859c0b-537c-460b-8c0b-ab4a5ca012f3)


### 24)	gzip Command

The gzip command is used to truncate the file size. It is a compressing tool. It replaces the original file by the compressed file having '.gz' extension.

Syntax: gzip <file1> <file2> <file3>..

![Screenshot 2025-03-11 135106](https://github.com/user-attachments/assets/23cc9953-c0ed-457b-8d11-e22c8a2858c7)


### 25)	sort Command

The sort command is used to sort files in alphabetical order.

Syntax:sort <file name>

![Screenshot 2025-03-11 135114](https://github.com/user-attachments/assets/22bb6c6b-15c4-4135-8fda-dcdd73b4f4a2)

 
### 26)	cal Command

The cal command is used to display the current month's calendar with the current date highlighted.

Syntax: cal

![Screenshot 2025-03-11 135119](https://github.com/user-attachments/assets/4be34bc3-d602-458f-942c-209fc309d208)


### 27)	clear Command

Linux clear command is used to clear the terminal screen.

Syntax: clear

![Screenshot 2025-03-11 135126](https://github.com/user-attachments/assets/fd7bc514-bd13-4adf-a879-5bffbdaaecac)


### 28)	mail Command

The mail command is used to send emails from the command line.

Syntax: mail -s "Subject" <recipient address>

![Screenshot 2025-03-11 135135](https://github.com/user-attachments/assets/1c622872-80c8-4b20-9c1b-224d65c3bd10)

 
### 29)	df Command

The df command is used to display the disk space used in the file system. It displays the output as in the number of used blocks, available blocks, and the mounted directory.

Syntax: df

![Screenshot 2025-03-11 135144](https://github.com/user-attachments/assets/db65cad2-42c9-409e-89b7-476c1d6a147b)


### 30)	find Command

The find command is used to find a particular file within a directory.

Syntax: find.-name”*.pdf”

## Result:

Thus, the execution of various Linux commands is executed successfully using Ubuntu OS.
