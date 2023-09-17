# LinuxPracticeProject

## In this project I will be outlining some command and their respective functions.

**What is a Linux command?** 

A Linux command is a program that runs on the command line.

**What is a Command Line Interface (CLI)**

A command line is an interface that accepts lines of text and processes them into instructions for your computer.

**a command general syntax is **'CommandName [option(s)] [parameter(s)]'***

**A command in Linux is case-sensitive*

1. **sudo** - super user do is a command used when performing a task that requires administrator privileges or access
   
![1 - correct](https://github.com/brightfav/LinuxPracticeProject/assets/107005839/cea5d37a-66fc-4ccd-9e01-cdfcba444dc2)

2. **pwd** - Print word directory(pwd) command is used to know the location or path of your current working directory

![3 pwd](https://github.com/brightfav/LinuxPracticeProject/assets/107005839/a546b930-a40b-4303-9a19-08415e661056)

3. **cd** - change directory command is used to change completely to another directory

![4 cd](https://github.com/brightfav/LinuxPracticeProject/assets/107005839/97e553d6-42e7-4ccd-9de4-e063f68ffd5d)

**note - after a change of directory from the home directory typing only 'cd' reverts back to the home directory*

4. **ls** - command is used to list all files and directories in the present directory or other directories when used with options and/or parameters

![5 ls](https://github.com/brightfav/LinuxPracticeProject/assets/107005839/07390420-d6b4-4939-bc6b-45e081a4e5bf)

the image above shows lists of files in the working directory

![7 ls list files in other directories](https://github.com/brightfav/LinuxPracticeProject/assets/107005839/77e1be57-5e74-4e1b-ab7a-c510cc890633)

the command in the image above shows a list of files and directories in another directory other than the current directory the ***ls*** is used with a parameter

![8 ls -R](https://github.com/brightfav/LinuxPracticeProject/assets/107005839/d40a2bdf-8960-46d0-9530-82de4cf5d7ea)

the **ls** command in the image above is used with an option **-R** which shows all the files and directories in the subdirectories

![9 ls -a](https://github.com/brightfav/LinuxPracticeProject/assets/107005839/35e44b6e-7641-4d9e-871f-1c9d5b80890c)

the **ls** command in the image above is used with an option **-a** which shows all hidden files together with the visible files

![10 ls -lh](https://github.com/brightfav/LinuxPracticeProject/assets/107005839/1a03845b-16fd-4e7e-b9e0-3e1e599fc761)

the **ls** command in the image above is used with an option **-lh** which output the file size in understandable format

5. **cat** command list, combines and writes file content to a standard output format

![11 cat](https://github.com/brightfav/LinuxPracticeProject/assets/107005839/8cf510ae-b697-4e96-8781-d4b6a791ece2)  


in the image below the ***cat*** command is used with parameters to combine two files to give a third file  

the command is written as **cat filename1.txt filename2.txt > filename3.txt** combine filename1.txt and filename2.txt to give output name  filename3.txt

![12 cat combine](https://github.com/brightfav/LinuxPracticeProject/assets/107005839/fb88f1d7-4401-4278-8855-4b42860c5fe5)

in the image below the the **cat** command is typed in reverse as **tac**

the **tac** command outputs the content of a file in reverse from down-up

![13 cat display in reverse](https://github.com/brightfav/LinuxPracticeProject/assets/107005839/0c946a5f-4569-48a1-aabe-23b3a84d57c4)

6. **cp** command is used to copy files or directories and their content

in the image below the cp command is used to copy *bright* file to another directory

![14 cp](https://github.com/brightfav/LinuxPracticeProject/assets/107005839/9a890878-22fc-4f3c-b135-7996fc07e22b)


in the image below the cp command is used with other parameters to copy two different files to another directory using **cp filename1.txt filename2.txt filename3.txt /home/username/Documents** command format

![15 cp copy two or more files from one directory to another](https://github.com/brightfav/LinuxPracticeProject/assets/107005839/ef3b934c-f13f-4700-a5c2-8a5e04d0ef77)


in the image below the cp command is used with other parameters to copy the content of a file to a new file in the same directory using **cp filename1.txt filename2.txt** command format

![16 - cp copy the content of one file to the other](https://github.com/brightfav/LinuxPracticeProject/assets/107005839/6a650976-f690-436a-b977-a5a80e244e7c)


in the image below the cp command is used with -R option to copy an entire directory to another directory using **cp -R /home/username/Documents /home/username/Documents_backup** command format

![17 cp copy an entire directory to another directory](https://github.com/brightfav/LinuxPracticeProject/assets/107005839/47d8690a-190c-4fe5-a388-8f65723bd9e9)

7. **mv** command is primarily used to move and rename files and directories and it does not produce an output upon completion.

type **mv** followed by the filename and the destination directory suing this code formant **mv sqlite_commands1.sh /home/ubuntu/CommandsLinux**

the image below shows the execution of the **mv** command

![18 mv move a file to a directory](https://github.com/brightfav/LinuxPracticeProject/assets/107005839/55e4315f-20d7-4a2a-92f1-e0b3101e71f7)

the **mv** command can also be used to rename a file using **mv sqlite_commands.sh sql_commands.sh** code format. the file name is typed followed by the new file name.

the image below shows the output of a file renamed using the **mv**command

![19 mv rename a file](https://github.com/brightfav/LinuxPracticeProject/assets/107005839/5b7fe7ec-6a97-410c-8100-deea1f4c9c1b)
























   
