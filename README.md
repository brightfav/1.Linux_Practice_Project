# LinuxPracticeProject

## In this project I will be outlining some command and their respective functions.

**What is a Linux command?** 

A Linux command is a program that runs on the command line.

**What is a Command Line Interface (CLI)**

A command line is an interface that accepts lines of text and processes them into instructions for your computer.

**a command general syntax is **'CommandName [option(s)] [parameter(s)]'***

**A command in Linux is case-sensitive*


### **sudo**  

superuser do is a command used when performing a task that requires administrator privileges or access
   
![1 - correct](https://github.com/brightfav/LinuxPracticeProject/assets/107005839/cea5d37a-66fc-4ccd-9e01-cdfcba444dc2)


### **pwd** 

Print word directory(pwd) command is used to know the location or path of your current working directory

![3 pwd](https://github.com/brightfav/LinuxPracticeProject/assets/107005839/a546b930-a40b-4303-9a19-08415e661056)


### **cd** 

change directory command is used to change completely to another directory

![4 cd](https://github.com/brightfav/LinuxPracticeProject/assets/107005839/97e553d6-42e7-4ccd-9de4-e063f68ffd5d)

**note - after a change of directory from the home directory typing only 'cd' reverts back to the home directory*


### **ls** 

this command is used to list all files and directories in the present directory or other directories when used with options and/or parameters

the image below shows lists of files in the working directory

![5 ls](https://github.com/brightfav/LinuxPracticeProject/assets/107005839/07390420-d6b4-4939-bc6b-45e081a4e5bf)

the command in the image below shows a list of files and directories in another directory other than the current directory the ***ls*** is used with a parameter

![7 ls list files in other directories](https://github.com/brightfav/LinuxPracticeProject/assets/107005839/77e1be57-5e74-4e1b-ab7a-c510cc890633)

the **ls** command in the image below is used with an option **-R** which shows all the files and directories in the subdirectories

![8 ls -R](https://github.com/brightfav/LinuxPracticeProject/assets/107005839/d40a2bdf-8960-46d0-9530-82de4cf5d7ea)

the **ls** command in the image below is used with an option **-a** which shows all hidden files together with the visible files

![9 ls -a](https://github.com/brightfav/LinuxPracticeProject/assets/107005839/35e44b6e-7641-4d9e-871f-1c9d5b80890c)


the **ls** command in the image below is used with an option **-lh** which output the file size in understandable format

![10 ls -lh](https://github.com/brightfav/LinuxPracticeProject/assets/107005839/1a03845b-16fd-4e7e-b9e0-3e1e599fc761)


### **cat** 

this command list combines and writes file content to a standard output format

![11 cat](https://github.com/brightfav/LinuxPracticeProject/assets/107005839/8cf510ae-b697-4e96-8781-d4b6a791ece2)  

in the image below the ***cat*** command is used with parameters to combine two files to give a third file  

the command is written as **cat filename1.txt filename2.txt > filename3.txt** combine filename1.txt and filename2.txt to give output name  filename3.txt

![12 cat combine](https://github.com/brightfav/LinuxPracticeProject/assets/107005839/fb88f1d7-4401-4278-8855-4b42860c5fe5)

in the image below the the **cat** command is typed in reverse as **tac**

the **tac** command outputs the content of a file in reverse from down-up

![13 cat display in reverse](https://github.com/brightfav/LinuxPracticeProject/assets/107005839/0c946a5f-4569-48a1-aabe-23b3a84d57c4)


### **cp** 

command is used to copy files or directories and their content

in the image below the cp command is used to copy the *bright* file to another directory

![14 cp](https://github.com/brightfav/LinuxPracticeProject/assets/107005839/9a890878-22fc-4f3c-b135-7996fc07e22b)


in the image below the cp command is used with other parameters to copy two different files to another directory using the **cp filename1.txt filename2.txt filename3.txt /home/username/Documents** command format

![15 cp copy two or more files from one directory to another](https://github.com/brightfav/LinuxPracticeProject/assets/107005839/ef3b934c-f13f-4700-a5c2-8a5e04d0ef77)


in the image below the cp command is used with other parameters to copy the content of a file to a new file in the same directory using
**cp filename1.txt filename2.txt** 
command format

![16 - cp copy the content of one file to the other](https://github.com/brightfav/LinuxPracticeProject/assets/107005839/6a650976-f690-436a-b977-a5a80e244e7c)


in the image below the cp command is used with the -R option to copy an entire directory to another directory using the 
**cp -R /home/username/Documents /home/username/Documents_backup** 
command format

![17 cp copy an entire directory to another directory](https://github.com/brightfav/LinuxPracticeProject/assets/107005839/47d8690a-190c-4fe5-a388-8f65723bd9e9)


### **mv** 

command is primarily used to move and rename files and directories and it does not produce an output upon completion.

type **mv** followed by the filename and the destination directory using this code formant 
**mv sqlite_commands1.sh /home/ubuntu/CommandsLinux**

the image below shows the execution of the **mv** command

![18 mv move a file to a directory](https://github.com/brightfav/LinuxPracticeProject/assets/107005839/55e4315f-20d7-4a2a-92f1-e0b3101e71f7)

the **mv** command can also be used to rename a file using
**mv sqlite_commands.sh sql_commands.sh** code format. the file name is typed followed by the new file name.

the image below shows the output of a file renamed using the **mv**command

![19 mv rename a file](https://github.com/brightfav/LinuxPracticeProject/assets/107005839/5b7fe7ec-6a97-410c-8100-deea1f4c9c1b)


### **mkdir** 

command is used to create one or more directories at once and set permissions for each of them.

the basic syntax for this command is **mkdir [option] directory_name**

the image below shows the output for using the **mkdir** command to create a directory

![20 mkdir create a directory](https://github.com/brightfav/LinuxPracticeProject/assets/107005839/a1eb395d-f7f1-4cbe-8089-7e8b7c86fea9)

**mkdir** command is used to create a new directory in another directory  as shown in the image below

![21 mkdir create a new directory in a directory](https://github.com/brightfav/LinuxPracticeProject/assets/107005839/f928666f-8327-4633-86ea-98d2253f8fdb)


### **rmdir** 

command is used to delete an empty directory permanently. to run this command sudo privileges should be enabled.

the code output is shown in the image below

![22 rmdir Permanently remove an empty subdirectory](https://github.com/brightfav/LinuxPracticeProject/assets/107005839/582b78aa-a5ac-4dd6-ad2a-0939d8ab65a1)


### **rm**

command is used to delete files within a directory. To perform this command the user must have write permission.

*it is important to know the file(s) directory to avoid deleting important files*

the output of the command is shown in the image below

![23 rm delete file from a directory](https://github.com/brightfav/LinuxPracticeProject/assets/107005839/8dc7907d-a18d-48ff-bc5e-7662bedf6aa8)

to remove multiple files type the command in this format **rm filename1 filename2 filename3**. the output of the command is in the image below

![24 rm delete multiple files](https://github.com/brightfav/LinuxPracticeProject/assets/107005839/72ca4482-5806-4fe6-a1b1-5b2361e32c1f)


### **touch**

command allows for the creation of an empty file.

the image below shows the output of **touch** command

![Uploading 25 touch create a file.PNG

![25 touch create a file](https://github.com/brightfav/LinuxPracticeProject/assets/107005839/d791a474-7f2b-43b3-a727-a158b12b2897)


### **locate** 

command is used to find a file in the database system adding the option of -i turns off case sensitivity.

this command is important because it finds a file although the exact name is not known

the output of the command is shown in the image below

![26 locate files](https://github.com/brightfav/LinuxPracticeProject/assets/107005839/4cb571cf-551b-489d-959e-402330f0ad4b)


### **find**

command is used to search for a file within a specific directory.

use this syntax ***find [option] [path] [expression]*** when using the *find* command

the output of the command is shown in the image below

![27 find a file in a specific directory and its sub directory](https://github.com/brightfav/LinuxPracticeProject/assets/107005839/adcd0634-1b37-4b3b-abc4-61a357e3e8b3)


### **grep** 

command is used to find a word by searching through all text in a specific file.

when a match for the searched word is found it prints all the lines that contain the searched word.

the image below shows the output of the *grep* command

![28 grep find a specific word in a file](https://github.com/brightfav/LinuxPracticeProject/assets/107005839/c2862971-5df3-4c75-a3bd-abe1f74aa0a6)


### **df** 

command is used to report the system disk space usage and displays results in percentage and kilobyte.

**df [options] [file]** is the general syntax for the *df* command

this command can be used with various options such as -h, -k, -T

the image below shows the output of the *df* command with various options 

![30 df -h df -k df -T see the current directory system disk usage](https://github.com/brightfav/LinuxPracticeProject/assets/107005839/0988ec2e-1fff-4510-b593-e065627a12e8)


### **du**

command is used to check how much space a file or directory takes

note that the file or directory path must be specified

the image below shows the output of the *du* command with various options 

![31 du know how much space a file or directory takes](https://github.com/brightfav/LinuxPracticeProject/assets/107005839/ea3913ed-d56c-46f5-aca7-3490db2fc3f5)


### **head**

this command displays the first ten lines of a text adding an option will specify the number of lines to be shown

the common syntax for *head* command is **head [option] [file]**

the image below shows the output of the *head* command with an option

![32 head command to see the begining content of a file](https://github.com/brightfav/LinuxPracticeProject/assets/107005839/fa53e02d-33d4-4e9a-8a83-abbccb586d49)


### **tail**

command displays the last ten lines of a file. it is useful to determine if a file has new data or to read error messages.

the general syntax of *tail* command is **tail [option] [file]**

the image below shows the output of the *tail* command with an option

![33 tail command to see the end content of a file](https://github.com/brightfav/LinuxPracticeProject/assets/107005839/7f9d9428-9c09-412e-8164-bc957a5948fa)


### **diff**

command compares two contents of a file line by line and afterward will display parts that do not match.

this command can be used to alter a program instead of writing the source code 

the general syntax of *diff* command is **diff [option] file1 file2**

the image below shows the output of the *diff* command 

![34 diff compare two files](https://github.com/brightfav/LinuxPracticeProject/assets/107005839/9d27f188-42ba-424e-b203-7103251e800c)


### **tar**

command archives multiple files into TAR file format

the general syntax of *tar* command is **tar [options] [archive_file] [file or directory to be archived]** 

This command can be used with various options such as -x, -t, and -u.

the image below shows the output of the *tar* command 

![35 tar create an archive](https://github.com/brightfav/LinuxPracticeProject/assets/107005839/de80e161-22f6-42d8-8956-618b10868469)


### **chmod** 

command modifies a file or directory read, write and execute permissions.

there are three user classes in linux which are owner, group member and others.

the general syntax of the *chmod* command is **chmod [option] [permission] [file_name]** 

This command can be used with various options such as -c, -v, and -f.

the image below shows the output of the *chmod* command 

![36 chmod change read or write permission of a file or directory of a user](https://github.com/brightfav/LinuxPracticeProject/assets/107005839/2e7ab6c5-f0af-4262-bb02-e070c08dfd7f)


### **chown**

command allows for the change of ownership of a file, directory, or symbolic link to a specified username. 

the general syntax of *chown* command is **chown [option] owner[:group] file(s)**

the image below shows the output of the *chown* command 

![37 change of file or directory ownership to another user](https://github.com/brightfav/LinuxPracticeProject/assets/107005839/17899c29-4f36-4697-a503-74018fe554b6)


### **ping** 

command is used to check if a network server is reachable. it can also be used to troubleshoot various connectivity issues.

the general syntax of *ping* command is **ping [option] [hostname_or_IP_address]**

the image below shows the output of the *ping* command 

![39 ping test connection to a server or website](https://github.com/brightfav/LinuxPracticeProject/assets/107005839/0cf039d0-98c3-4326-852e-01dfc70985a8)


### **wget**

command lets you download files from the internet. it works in the background without hindering other running processes

the general syntax of *wget* command is **wget [option] [url]**

The image below shows the output of the *wget* command 

![40 wget download files from the internet](https://github.com/brightfav/LinuxPracticeProject/assets/107005839/3722cba7-db71-419f-9efe-bd1c69d56fb1)


### **uname** 

command prints detailed information about your Linux system and hardware.

it displays the machine name, operating system, and kernel.

the general syntax of *uname* command is **uname [option]**

This command can be used with various options such as -a, -s, and -n

The image below shows the output of the *uname* command 

![41 uname give detailed information about linux system](https://github.com/brightfav/LinuxPracticeProject/assets/107005839/6aa7af23-f561-4e8a-8e95-7122430a1581)


### **top** 

command displays all running processes and a dynamic real-time view of the current system. it sums up resource utilization from CPU to memory usage.

this command is useful to identify and terminate a process that may use too many system resources.  

the general syntax of *top* command is **top**

The image below shows the output of the *top* command

![42 top display all running process in the linux server](https://github.com/brightfav/LinuxPracticeProject/assets/107005839/c1d5eaf2-3012-4fa8-93b0-eaecd16841ca)


### **history**

command will list up to 500 previously executed commands allowing you to reuse them. Only users with sudo privileges can execute this command.

the general syntax of *history* command is **history [option]**

This command can be used with various options such as -c, -d, and -a

The image below shows the output of the *history* command

![43 history list all previously listed commands](https://github.com/brightfav/LinuxPracticeProject/assets/107005839/56c6ba34-a830-4391-84d3-bab1c554be09)


### **man** 

provides a user manual of any commands or utilities you can run in the terminal including name, description, and options.

the general syntax of *man* command is **man [command_name]** 

the syntax to use to specify the displayed section is **man [option] [section_number] [command_name]**

The image below shows the output of the *man* command 

![44 man provides a user manual of any command or utility including name option and utilities](https://github.com/brightfav/LinuxPracticeProject/assets/107005839/0445e9aa-8d6d-4112-aa53-68098ce7b558)


### **zip** 

command compresses files into a zip file

this command is useful for archiving files and directories to reduce disk usage

the general syntax of *zip* command is **zip [options] zipfile file1 file2….**

the general syntax of *unzip* command is **unzip [option] file_name.zip**

The image below shows the output of the *zip* and *unzip* command 

![45 zip and uzip command to compress a file and decopress a zip file](https://github.com/brightfav/LinuxPracticeProject/assets/107005839/b232e281-bac5-4697-aad8-7c6807a9b59c)


### **hostname**

command is used to know the system's hostname. it is executable with or without a command.

the general syntax of *hostname* command is **hostname [option]**

This command can be used with various options such as -a, -A, and -i

The image below shows the output of the *hostname* command

![46 hostname know a server name alias and ip adress](https://github.com/brightfav/LinuxPracticeProject/assets/107005839/b939b7eb-6e58-4059-a9fd-2d1c59a60d86)


### **useradd**  **userdel**

*useradd* command is used to add or create a new user and *userdel* is used to remove or delete a user 

you need root or sudo privileges to run these commands 

the general syntax of *useradd* command is **useradd [option] username** 

the general syntax of *userdel* command is **userdel username**

The image below shows the output of the *useradd* and *userdel* command

![47 useradd userdel add or remove a user in linux](https://github.com/brightfav/LinuxPracticeProject/assets/107005839/b9f3bb4e-c882-4945-995c-e250da60b3e3)


### **apt-get** 

command lets you retrieve information and bundles from authenticated sources to manage, update, remove, and install software and its dependencies.

running this command requires you to have sudo or root privileges

the general syntax of *apt-get* command is **apt-get [options] (command)**

The image below shows the output of the *apt* command

![49 apt install install a library from a good source](https://github.com/brightfav/LinuxPracticeProject/assets/107005839/9ddf105e-eb69-44c3-acd6-360df55f3382)

![49 apt install install a library from a good source using root access](https://github.com/brightfav/LinuxPracticeProject/assets/107005839/61f2b7b8-86f1-4e72-894c-b88724ecb3f4)


### **nano** **vi** **jed** 

command allows you to edit and merge files via a text editor such as nano, jed, and vi. others come with the operating system but jed has to be installed.

the general syntax of *nano* command is **nano [filename]**

the general syntax of *vi* command is **vi [filename]**

the general syntax of *jed* command is **jed [filename]**


The image below shows the output of the *nano* command

![48 nano edit a file on linux using a text editor](https://github.com/brightfav/LinuxPracticeProject/assets/107005839/d2a65baf-8ca9-4005-96ae-d25565fba5a4)


The image below shows the output of the *vi* command

![51 vi gives more info about a file](https://github.com/brightfav/LinuxPracticeProject/assets/107005839/4b80c578-3934-4d34-97b5-3e646b159fea)


The image below shows the output of the *jed* command

![50 jed used to edit a file](https://github.com/brightfav/LinuxPracticeProject/assets/107005839/dced2b17-ac3e-40bd-9955-c55973b18aa2)


### **alias** 

command allows you to create a shortcut with the same functionality as a command, file name, or text.

when executed it instructs the shell to replace one string with another.  

the general syntax of *alias* command is **alias Name=String**

### **unalias** 
 
command deletes an existing alias

the general syntax of *unalias* command is **unalias [alias_name]**

The image below shows the output of the *alias* and *unalias* command

![52 alias create a shortcut for a command and unalias removes the shortcut for an assigned command](https://github.com/brightfav/LinuxPracticeProject/assets/107005839/46b84282-7c9c-401e-b688-778b25c29cfa)


### **su** 

command allows you to run a different program as a different user. It changes the administrative account in the current log-in session.

the general syntax of *su* command is **su [options] [username [argument]]**

when executed without any option or argument the *su* command runs through root privileges and will prompt you to authenticate and use sudo privileges temporarily. 

This command can be used with various options such as -p, -s, and -l

The image below shows the output of the *su* command

![53 su - switch user](https://github.com/brightfav/LinuxPracticeProject/assets/107005839/f0c8e3a0-8234-4300-8add-821089c8bba6)


### **htop** 

command is an interactive program that monitors system resources and server processes in real time

the general syntax of *htop* command is **htop [options]**

This command can be used with various options such as -d, -C, and -h

The image below shows the output of the *htop* command 

![54 htop live process monitoring](https://github.com/brightfav/LinuxPracticeProject/assets/107005839/13ee49ef-39ac-4656-bdb6-cdf23042f88b)



### **ps** 

command produces a snapshot of all running processes in the Linux system

Executing the ps command without an option or argument will list the running processes in the shell

This command can be used with various options such as -T, -u, and -A

The image below shows the output of the *ps* command 

![55 ps produce a snapshot of all running processes](https://github.com/brightfav/LinuxPracticeProject/assets/107005839/186469b6-1a72-4e6c-a26e-4dd2a7de0ddf)














 


















































   
