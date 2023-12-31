# linux
## lab1

### 1. Install CentOS /RHEL
#### 
2. What is the difference between cat and more command?
 cat: 
The cat command stands for "concatenate" and is primarily used to display the entire contents of one or more files without any pagination.
It is commonly used to concatenate and display the contents of multiple files in the terminal.
 
  
 more:      
The more command is used to display the contents of a file one screen at a time, allowing the user to navigate through the output.
It pauses after each screenful of information and waits for a keypress to continue to the next screen or to exit the display.
 
### 3. What is the difference between rm and rmdir using man?
#### rm
![rm](https://github.com/EngAlaaKamal/linux/assets/147073553/9ca78e23-0bea-4f63-a617-c146b93b35e4)


#### rmdir
![rmdir](https://github.com/EngAlaaKamal/linux/assets/147073553/83f1f634-b979-4ada-bd7f-c434ee27626e)




### 4. Create the following hierarchy under your home directory:
 (https://github.com/EngAlaaKamal/linux/assets/147073553/e5a1442f-4b1a-47bb-8613-b78faf593f90)
 (https://github.com/EngAlaaKamal/linux/assets/147073553/32882ded-9bc3-4b4f-afdb-8598a0d2a558)

#### a. Remove dir11 in one-step. What did you notice? And how did you overcome that?
(https://github.com/EngAlaaKamal/linux/assets/147073553/07faf4cc-4492-4668-b4ed-76cb3d83e5ea)


#### b. Then remove dir12 using rmdir –p command. State what happened to the
(https://github.com/EngAlaaKamal/linux/assets/147073553/1a455c14-f69c-4743-bc77-9c55c3226aca)

#### c. The output of the command pwd was /home/user. Write the absolute and relative path for the file mycv
(https://github.com/EngAlaaKamal/linux/assets/147073553/3933a57a-af5d-4539-a78d-54671368823a)

 5&6 Copy the /etc/passwd file to your home directory making its name is mypasswd.
 & Rename this new file to be oldpasswd.
![lab1-5,6](https://github.com/EngAlaaKamal/linux/assets/147073553/8fae124f-69db-487e-8a4e-d36124fa33cb)


### 7. You are in /usr/bin, list four ways to go to your home directory
![lab1-7](https://github.com/EngAlaaKamal/linux/assets/147073553/be58a602-48c7-4b56-9642-745149e3eeca)

### 8. List Linux commands in /usr/bin that start with letter w
[lab1-8](https://github.com/EngAlaaKamal/linux/assets/147073553/bd1a82e9-ceca-4632-a1d0-5f44a348a7c7)

 ## 9&10 Display the first 4 lines of /etc/passwd & Display the last 7 lines of /etc/passwd 
 (https://github.com/EngAlaaKamal/linux/assets/147073553/5e444c53-6252-48f3-bb53-8532375d1b13)

### ( 11 & 12 & 13) Display the man pages of passwd the command and the file sequentially in one command & Display the man page of the passwd file & Display a list of all the commands that contain the keyword passwd in their man page.

![lab1-11,12,13](https://github.com/EngAlaaKamal/linux/assets/147073553/9c5014c8-9993-4f62-ade4-15ac7846141a)





#### ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------####


## LAB2 ##

## 1. Create a user account with the following attribute
 username: islam
 Fullname/comment: Islam Askar
 Password: islam
![lab2-1](https://github.com/EngAlaaKamal/linux/assets/147073553/867a0c36-eec3-48da-bae3-035f07ecccc2)


## 2. Create a user account with the following attribute
 Username: baduser
 Full name/comment: Bad User
 Password: baduser

![lab2-2](https://github.com/EngAlaaKamal/linux/assets/147073553/a47ac289-f6da-4ed6-b98e-51f8ce32ef6f)

## 3.4.5 Create a supplementary (Secondary) group called pgroup with group ID of 3000.&& Create a supplementary group called badgroup && Add islam user to the pgroup group as a supplementary group
![lab2-3,4,5](https://github.com/EngAlaaKamal/linux/assets/147073553/68da9a89-f523-4860-b53d-cddc6f04b002)


## 6. Modify the password of islam's account to password
![lab2-6](https://github.com/EngAlaaKamal/linux/assets/147073553/e8f4b14a-d09a-4a76-9cc8-9d6f334f3031)


## 7. Modify islam's account so the password expires after 30 days
![lab2-7](https://github.com/EngAlaaKamal/linux/assets/147073553/a94fd571-1ad6-4511-9577-c56a8ca64770)


## 8. Lock bad user account so he can't log in

![lab2-8](https://github.com/EngAlaaKamal/linux/assets/147073553/87018939-6ae1-40f6-8d25-c9212c36d55e)

## 9. Delete bad user account
![lab2-9](https://github.com/EngAlaaKamal/linux/assets/147073553/4e1cb69a-7ee6-482d-846e-25616471d424)


## 10. Delete the supplementary group called badgroup.

![lab2-10](https://github.com/EngAlaaKamal/linux/assets/147073553/69d5ac17-234b-4ab0-862b-fcb309dd1238)

## 13. Create a folder called myteam in your home directory and change its permissions to read only for the owner.

![lab2-13](https://github.com/EngAlaaKamal/linux/assets/147073553/19368eab-d6eb-4db4-bd1f-19fbef1fdea7)

## 14. Log out and log in by another user
![lab2-14](https://github.com/EngAlaaKamal/linux/assets/147073553/473d5f70-f55a-44b3-b706-ab3bae9ed055)


## 15. Try to access (by cd command) the folder (myteam)

![lab2-15](https://github.com/EngAlaaKamal/linux/assets/147073553/577e03e6-25f1-45fd-9a6c-01445efa3556)

## 16. Using the command Line
 Change the permissions of oldpasswd file to give owner read and write
permissions and for group write and execute and execute only for the others
(using chmod in 2 different ways)
![lab2-16-a](https://github.com/EngAlaaKamal/linux/assets/147073553/3ed995bd-e7b4-4edb-84f5-4d799813d919)


![lab2-16-aa](https://github.com/EngAlaaKamal/linux/assets/147073553/59413d4e-41a9-4d76-af93-054ef2e6f6f7)


 Change your default permissions to be as above.
![lab2-16-b](https://github.com/EngAlaaKamal/linux/assets/147073553/9358275c-5a2e-4e42-b155-0e4df36590d0)


 What is the maximum permission a file can have, by default when it is just
created? And what is that for directory.

{
File Permissions (666):

Owner (user): Read (r), Write (w)
Group: Read (r), Write (w)
Others: Read (r), Write (w)
Directory Permissions (777):

Owner (user): Read (r), Write (w), Execute (x)
Group: Read (r), Write (w), Execute (x)
Others: Read (r), Write (w), Execute (x)

}

 Change your default permissions to be no permission to everyone then create a
directory and a file to verify.
## Set the umask to 077 (no permission for everyone)
umask 077
 


## 17. What are the minimum permission needed for:
 Copy a directory (permission for source directory and permissions for target
parent directory)

Source file(Minimum Permissions): r
distination directory (Minimum Permissions):w
---------------------------------------------------------------

 Copy a file (permission for source file and and permission for target parent
directory)

Source Directory (Minimum Permissions): rx
distination directory (Minimum Permissions):w
---------------------------------------------------------------------

 Delete a file


To delete a file, the minimum permission required is the write permission (w) on the directory containing the file. This allows the user to modify the directory by removing or adding files.
-----------------------------------------------------------
 Change to a directory 

To make the minimum change to a directory, need the execute permission (x) on that directory.
-------------------------------------------------------------
 List a directory content (ls command)

minimum permision is r
--------------------------------------------------
 View a file content (more/cat command)

minimum permision is r
--------------------------------------------------

 Modify a file content

minimum permision is w
----------------------------------------------------------

## 18. Create a file with permission 444. Try to edit in it and to remove it? Note what happened.
touch myfile.txt
chmod 444 myfile.txt

gedit myfile.txt


## 19. What is the difference between the “x” permission for a file and for a directory?


The meaning of the "x" (execute) permission differs between a file and a directory in Linux.

For a File:
Execute (x) Permission on a File: the "x" permission means the ability to execute the file as a program. It allows the user to run the file if it contains executable code.

For a Directory: the "x" permission means the ability to access (enter) the directory and execute certain operations within the directory.
Without the execute permission on a directory, you cannot access its contents 

### ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------###

### LAB3 ###

## 1. Using vi write your CV in the file mycv. Your CV should include your name, age, school,college, experience,...

(https://github.com/EngAlaaKamal/linux/assets/147073553/321fcca4-4902-44c3-919f-d86203ff563e)


## 2. Open mycv file using vi command then: Without using arrows state how to:
a. Move the cursor down one line at time. ## j
b. Move the cursor up one line at time.## k
c. Search for word age ## /age
(https://github.com/EngAlaaKamal/linux/assets/147073553/4da81a97-b44f-41f0-a459-df5f939f1899)


d. Step to line 5 (assuming that you are in line 1 and file is more than 5 lines).(:5)
(https://github.com/EngAlaaKamal/linux/assets/147073553/fb9ef61d-2105-4a4c-8537-c5787a1bc1c5)


e. Delete the line you are on and line 5.(3,5d)
(https://github.com/EngAlaaKamal/linux/assets/147073553/71226df1-18ce-4339-824a-9c6c307c7e7d)

f. How to step to the end of line and change to writing mode in one-step.(A)
(https://github.com/EngAlaaKamal/linux/assets/147073553/c8fb8b94-6546-45e2-8598-07c641d2cc0a)

## 3. List the available shells in your system.
![lab3-3](https://github.com/EngAlaaKamal/linux/assets/147073553/fc473fad-2d11-4ba2-a28f-9d901357d355)


## 4. List the environment variables in your current shell.
![lab3-4](https://github.com/EngAlaaKamal/linux/assets/147073553/b2d56756-9904-48f8-bbf7-c06ead94cdbc)


## 5. List all of the environment variables for the bash shell.
![lab3-5](https://github.com/EngAlaaKamal/linux/assets/147073553/bde9f35d-febb-4b7c-ac89-0cc0895ac599)


## 6. What are the commands that list the value of a specific variable?
![lab3-6](https://github.com/EngAlaaKamal/linux/assets/147073553/96baba8e-5f46-438a-ac06-43b5057df0b7)


## 7. Display your current shell name.
![lab3-7](https://github.com/EngAlaaKamal/linux/assets/147073553/a1aab642-9e7b-4e38-a293-f4cb640d28e0)


## 8. State the initialization files of: sh, ksh, bash.
- sh (Bourne Shell):
      /etc/profile
      ~/.profile

- ksh (Korn Shell):
      /etc/profile
      ~/.profile

- bash (Bash Shell):
  - /etc/profile, /etc/bash.bashrc
    - Non-interactive login (when started as a login shell): ~/.bash_profile, ~/.bash_login, ~/.profile
  - User-specific:
    - Interactive non-login (when started in an existing session): ~/.bashrc


## 9. Edit in your profile to display date at login and change your prompt permanently.
![lab3-99](https://github.com/EngAlaaKamal/linux/assets/147073553/51016734-b735-436a-bff6-8125aeaf1b69)



## 10.Execute the following command :
echo \ then press enter
What is the purpose of \ ?
Notice the prompt ”>” what is that? and how can you change it from “>” to “:”.
## 11.Create a Bash shell alias named ls for the “ls –l” command
(https://github.com/EngAlaaKamal/linux/assets/147073553/c94c31e0-73f6-467c-b723-2ddf0067da0d)


#### ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------- ####

## LAB5 ##

## 1. Compress a file by compress, gzip, zip commands and decompress it again. State the differences between compress and gzip commands.
![lab5-1-a](https://github.com/EngAlaaKamal/linux/assets/147073553/858d3ec8-ebc2-44a4-83e3-e933246d2d3d)
![lab5-1-b](https://github.com/EngAlaaKamal/linux/assets/147073553/94952561-c3ac-4e26-8ff4-4922e49789e0)


## 2. What is the command used to view the content of a compressed file.
![lab5-2](https://github.com/EngAlaaKamal/linux/assets/147073553/4cf8d976-c54e-49b6-b331-2a6bc172cbb1)


## 3. Backup /etc directory using tar utility.
![lab5-3](https://github.com/EngAlaaKamal/linux/assets/147073553/2abf92db-5155-4c85-bd12-79f14a3ad285)


## 4. Starting from your home directory, find all files that were modified in the last two day.
![lab5-4](https://github.com/EngAlaaKamal/linux/assets/147073553/5a52d40e-fff0-422e-a1eb-060917cb5b22)


## 5. Starting from /etc, find files owned by root user.
![lab5-5](https://github.com/EngAlaaKamal/linux/assets/147073553/9dd66f92-e9d3-4fb1-99bc-310c08a0633c)


## 6. Find all directories in your home directory.
![lab5-61](https://github.com/EngAlaaKamal/linux/assets/147073553/424ae27e-daa8-4f63-92ba-391d80564c72)
![lab5-62](https://github.com/EngAlaaKamal/linux/assets/147073553/ec47105c-94fc-4731-b66c-195932ebf214)


## 7. Write a command to search for all files on the system that, its name is “.profile”.
![lab5-7](https://github.com/EngAlaaKamal/linux/assets/147073553/6c8c13e8-b826-4308-8a5c-7a0e7e7bc066)


## 8. Identify the file types of the following: /etc/passwd, /dev/pts/0, /etc, /dev/sda
![lab5-8](https://github.com/EngAlaaKamal/linux/assets/147073553/eb354275-05dc-4804-bb08-9a40b13e3a8a)


## 9. List the inode numbers of /, /etc, /etc/hosts.
![lab5-9](https://github.com/EngAlaaKamal/linux/assets/147073553/e872fa8e-eb12-4875-bd35-8b416cedbd71)


## 10. Copy /etc/passwd to your home directory, use the commands diff and cmp, and Edit in the file you copied, and then use these commands again, and check the output.
![lab5-10](https://github.com/EngAlaaKamal/linux/assets/147073553/8382da74-6270-4953-af6a-fe8416574952)


## 11. Create a symbolic link of /etc/passwd in /boot.
![lab5-11](https://github.com/EngAlaaKamal/linux/assets/147073553/4d65586e-1387-4672-ac69-f1685218e91d)

 
## 12. Create a hard link of /etc/passwd in /boot. Could you? Why?
![lab5-12](https://github.com/EngAlaaKamal/linux/assets/147073553/6588e5de-43c2-45cd-a992-907ad9987e49)

#### ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------###

## shell script lab 1 ##

Using sed utility
## 1- Display the lines that contain the word “lp” in /etc/passwd file.
![bach1-1](https://github.com/EngAlaaKamal/linux/assets/147073553/15e47379-2336-4639-8c1f-3889178a1429)


## 2- Display /etc/passwd file except the third line.
![bach1-2](https://github.com/EngAlaaKamal/linux/assets/147073553/f099909e-1620-440f-a664-82ddbbe20c9d)


## 3- Display /etc/passwd file except the last line.
![bach1-3](https://github.com/EngAlaaKamal/linux/assets/147073553/28dc7733-15f4-4b39-98fa-9815e142c64a)


## 4- Display /etc/passwd file except the lines that contain the word “lp”.
![bach1-4](https://github.com/EngAlaaKamal/linux/assets/147073553/0d38d3ce-d3a9-4438-bcf1-37ddcf236c87)


## 5- Substitute all the words that contain “lp” with “mylp” in /etc/passwd file.
![bach1-5](https://github.com/EngAlaaKamal/linux/assets/147073553/d1cc96d6-bd6b-43b0-82b9-908b396e610a)


Using awk utility
## 1- Print full name (comment) of all users in the system.
![bach1-awk1](https://github.com/EngAlaaKamal/linux/assets/147073553/5121ee58-f451-4b4c-837e-11856f94462b)


## 2- Print login, full name (comment) and home directory of all users.( Print each line preceded by a line number)
![bach1-awk2](https://github.com/EngAlaaKamal/linux/assets/147073553/1fd5408a-efa3-492b-8e9c-dbb9f6c16d4b)


## 3- Print login, uid and full name (comment) of those uid is greater than 500
![bach1-awk3](https://github.com/EngAlaaKamal/linux/assets/147073553/8a8645a7-179b-48b6-b569-bdbf05e17b0a)


## 4- Print login, uid and full name (comment) of those uid is exactly 500
![bach1-awk4](https://github.com/EngAlaaKamal/linux/assets/147073553/ecce904c-48bb-4bf3-bf32-80e370112c20)


## 5- Print line from 5 to 15 from /etc/passwd
![bach1-awk5](https://github.com/EngAlaaKamal/linux/assets/147073553/b6cd5aad-d0fa-4c21-b335-0d9988085580)


## 6- Change lp to mylp
![bach1-awk6](https://github.com/EngAlaaKamal/linux/assets/147073553/8c926fe2-ad09-4d27-ad20-f160fe12cb10)


## 7- Print all information about greatest uid.
![bach1-awk7](https://github.com/EngAlaaKamal/linux/assets/147073553/c20dfdca-3d1d-4103-97d3-33f06a07d6db)


## 8- Get the sum of all accounts id’s.
![bach1-awk8](https://github.com/EngAlaaKamal/linux/assets/147073553/c414f979-4e8a-44f9-8540-fa65cfc94f98)



 
#### ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------###

## shell script lab 2 ##

## 1. Create a script that asks for user name then send a greeting to him.
![bash2-1](https://github.com/EngAlaaKamal/linux/assets/147073553/70b707a6-e2c7-45a6-8157-8b09dcd7d21e)


## 2. Create a script called s1 that calls another script s2 where:
     a. In s1 there is a variable called x, it's value 5
     b. Try to print the value of x in s2 by two different ways.
![bash2-2a](https://github.com/EngAlaaKamal/linux/assets/147073553/26ee1a69-ed71-44ea-a8ef-077de3c88200)
![bash2-2b](https://github.com/EngAlaaKamal/linux/assets/147073553/92e571a3-994e-492a-b4af-a53d03364c07)
![bash2-2c](https://github.com/EngAlaaKamal/linux/assets/147073553/b097c33e-33bb-4286-b7c3-da4d39644975)

     
## 3. Create a script called mycp where:
    a. It copies a file to another
    b. It copies multiple files to a directory.
![bash2-3](https://github.com/EngAlaaKamal/linux/assets/147073553/169b2caa-5509-46dd-867e-880a06769a01)

    
## 4. Create a script called mycd where:
   a. It changed directory to the user home directory, if it is called without arguments.
   b. Otherwise, it change directory to the given directory.
![bash2-4](https://github.com/EngAlaaKamal/linux/assets/147073553/0b02bff1-e42a-4905-a2c6-eccca8f405e9)

   
## 5. Create a script called myls where:
   a. It lists the current directory, if it is called without arguments.
   b. Otherwise, it lists the given directory.
![bash2-5](https://github.com/EngAlaaKamal/linux/assets/147073553/735a4e90-c9ce-4f8a-9782-397f55e25899)

   
## 6. Enhance the above script to support the following options individually:
  a. –l: list in long format
  b. –a: list all entries including the hiding files.
  c. –d: if an argument is a directory, list only its name
  d. –i: print inode number
  e. –R: recursively list subdirectories

  ![bash2-6](https://github.com/EngAlaaKamal/linux/assets/147073553/54eb7a07-661d-453f-9802-c2bf0b7e38c7)
![bash2-66](https://github.com/EngAlaaKamal/linux/assets/147073553/16caad7f-c57a-4273-8140-2000120c24b6)


## 7. Create a script called mytest where:
a. It check the type of the given argument (file/directory)
b. It check the permissions of the given argument (read/write/execute)
![bash2-7](https://github.com/EngAlaaKamal/linux/assets/147073553/3083b502-7527-471b-8ac6-8183d52eb45d)
![bash2-7a](https://github.com/EngAlaaKamal/linux/assets/147073553/e46afa08-35bb-4582-8845-460198656f79)


## 8. Create a script called myinfo where:
a. It asks the user about his/her logname.
b. It print full info about files and directories in his/her home directory
c. Copy his/her files and directories as much as you can in /tmp directory.
d. Gets his current processes status.
![bash2-8](https://github.com/EngAlaaKamal/linux/assets/147073553/eb23c598-bef4-4f18-b53b-716742dfd2c2)
![bash2-8a](https://github.com/EngAlaaKamal/linux/assets/147073553/e6f92a62-35b7-476c-a191-8a4b6107b42d)



#### ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------###

## shell script lab 3 ##

## 1. Write a script called mycase, using the case utility to checks the type of character
entered by a user:
a. Upper Case.
b. Lower Case.
c. Number.
d. Nothing.
![bash3-1](https://github.com/EngAlaaKamal/linux/assets/147073553/8f85118a-66b2-4677-a704-bfcafb0776b3)
 

## 2. Enhanced the previous script, by checking the type of string entered by a user:
a. Upper Cases.
b. Lower Cases.
c. Numbers.
d. Mix.
e. Nothing.
![bash3-2](https://github.com/EngAlaaKamal/linux/assets/147073553/8751d963-ee79-4308-9e12-b1471f4fe207)
![bash3-2a](https://github.com/EngAlaaKamal/linux/assets/147073553/5add03f9-764c-4f60-bd72-0296c9ca78a0)


## 3. Write a script called mychmod using for utility to give execute permission to all files and
directories in your home directory.
![bash3-3](https://github.com/EngAlaaKamal/linux/assets/147073553/fdb4689b-2b5e-4750-b078-a7c47847a0f5)
![bash3-3a](https://github.com/EngAlaaKamal/linux/assets/147073553/465eddc0-7714-4574-95f6-885b7b4a386f)


## 4. Write a script called mybackup using for utility to create a backup of only files in your
home directory.
![bash3-4](https://github.com/EngAlaaKamal/linux/assets/147073553/60152d2d-db78-4837-907f-c553b65be32f)
![bash3-4a](https://github.com/EngAlaaKamal/linux/assets/147073553/419df941-00cc-481c-acde-e2688954815f)


## 5. Write a script called mymail using for utility to send a mail to all users in the system.
![bash3-5](https://github.com/EngAlaaKamal/linux/assets/147073553/e626d670-9244-4f4a-9b0b-c9974211263e)
![bash3-5a](https://github.com/EngAlaaKamal/linux/assets/147073553/9230bf5e-4e2c-4f68-ba53-c1a247258711)



## 6. Write a script called chkmail to check for new mails every 10 seconds. Note: mails are
saved in /var/mail/username.
![bash3-6](https://github.com/EngAlaaKamal/linux/assets/147073553/0e230895-f369-4848-b3ec-fc47acdd6bd2)
![bash3-6a](https://github.com/EngAlaaKamal/linux/assets/147073553/378f385d-bf83-4ea4-aa7b-14746ca577d4)

## 7. What is the output of the following script
typeset –i n1
typeset –i n2
n1=1
n2=1
while test $n1 –eq $n2
do
n2=$n2+1
print $n1
if [ $n1 –gt $n2 ]
then
break
else
continue
fi
n1=$n1+1
print $n2
done
![bash3-7](https://github.com/EngAlaaKamal/linux/assets/147073553/9877cb72-fc00-4176-a0ba-a100ce281dab)


## 8. Create the following menu:
a. Press 1 to ls
b. Press 2 to ls –a
c. Press 3 to exit
Using select utility then while utility.
![bash3-8](https://github.com/EngAlaaKamal/linux/assets/147073553/81dac54b-4d15-44f2-a344-06de5fc286d8)
![bash3-8a](https://github.com/EngAlaaKamal/linux/assets/147073553/d4cb3084-164f-493f-803c-b0220bf10802)


## 9. Write a script called myarr that ask a user how many elements he wants to enter in an
array, fill the array and then print it.
![bash3-9](https://github.com/EngAlaaKamal/linux/assets/147073553/21527db1-24ed-4e06-a570-a3e6b3d23e3b)
![bash3-9a](https://github.com/EngAlaaKamal/linux/assets/147073553/c6aca070-3e49-4756-b318-eb7f1e5568cc)


## 10.Write a script called myavg that calculate average of all numbers entered by a user.
Note: use arrays
![bash3-10](https://github.com/EngAlaaKamal/linux/assets/147073553/852fe39b-3e2d-41a5-9a78-2c5867760b6d)
![bash3-10a](https://github.com/EngAlaaKamal/linux/assets/147073553/5f97c227-faa8-4f3b-a280-6aef6399d5e9)


## 11.Write a function called mysq that calculate square if its argument.
![bash3-11](https://github.com/EngAlaaKamal/linux/assets/147073553/c05236a2-0058-47bc-9362-a9b44242d82b)
![bash3-11a](https://github.com/EngAlaaKamal/linux/assets/147073553/d1894960-300a-45ac-82d1-deb232425fa2)



#### ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------###

## admin2 lab 1 ##

# 1. Use systemctl to view the status of all the system services.
![labadmin1-1](https://github.com/EngAlaaKamal/linux/assets/147073553/048634d5-2144-4c6d-a078-363060c14a9b)
![labadmin1-1a](https://github.com/EngAlaaKamal/linux/assets/147073553/f9227eb6-cf07-4e7f-8945-328e0cc5a46e)
 

# 2. Change the default run level back to multi-user.target and reboot.
![labadmin1-2](https://github.com/EngAlaaKamal/linux/assets/147073553/f8cd9c09-7fc6-4014-8fd1-1cf81e91e2fe)


# 3. Send mail to the root user.
![labadmin1-3](https://github.com/EngAlaaKamal/linux/assets/147073553/b4be6e9e-62e8-4088-9592-ae0866e94669)


# 4. Verify that you have received this mail.

![labadmin4](https://github.com/EngAlaaKamal/linux/assets/147073553/a083af19-de0e-4eb2-a0d1-7aca118a927c)

# 5. Use  systemctl utility to stop postfix service &6. Send mail again to the root user.& 7. Verify that you have received this mail.&8. Use systemctl utility to start postfix service
![labadmin5-6-7-8](https://github.com/EngAlaaKamal/linux/assets/147073553/36da4b7e-eab3-4d23-b068-c83f329c22c5)

# 9. Verify that you have received this mail.
![labadmin8-9](https://github.com/EngAlaaKamal/linux/assets/147073553/6642ac48-883a-40b0-88be-dd46fdcdea55)

# 10. Edit in the GRUB2 configuration file and change the timeout variable equal 20 seconds.
![labadmin10-a](https://github.com/EngAlaaKamal/linux/assets/147073553/cb7baa2b-81d1-4ece-929b-249ca53a9347)
![labadmin10-b](https://github.com/EngAlaaKamal/linux/assets/147073553/a428cae9-62ca-44c0-bac0-2b2c64220567)

# 11.  Edit in the GRUB2 configuration file and change your default operating system
![labadmin11-a](https://github.com/EngAlaaKamal/linux/assets/147073553/b6ab05b7-bef0-4801-9fba-e67e99a9f350)
![labadmin11-b](https://github.com/EngAlaaKamal/linux/assets/147073553/b3af8a33-cb1d-4a07-8a4c-10baa167a40b)

# 12. You want to know some information about the status of the system every ten minutes today between the hours of  8:00 AM and 5:00 PM. to help investigate some performance issues you have been having. You suspect it might be memory related and want to keep an eye on those resources.
  
crontab -e
*/10 8-16 * * * /path/to/monitor_script.sh

# 13. Use mail as the root user to check for e-mail from the cron jobs you have scheduled.
sudo mail

# 14. How could you send the output from these cron jobs to another e-mail address (the manager user)?
*/10 * * * * /path/to/your/script.sh 2>&1 | mail -s "Cron Job Output" manager 

# 15. Use mail as the manager user to check for e-mail from the cron jobs you have scheduled.
mail

 

 
# 17. Attempt to run the command gnuplot. You should find that it is not installed
  >> yum list installed | grep gnuplot
 >> sudo yum install gnuplot


# 18. Search for plotting packages 
 >> yum search plotting

# 19. Get more information about the gnuplot package yum info gnuplot
 >> yum info gnuplot
# 20. Install gnuplot
>> sudo yum install gnuplot

# 21. Attempt to remove gnuplot sudo yum remove gnuplot
>> sudo yum remove gnuplot
# 22. Attempt to remove gunplot-common   
>> sudo yum remove gunplot-common  
# 23. List all installed packages 
>> yum list installed
# 24. View files in the initscripts package 
>> rpm -ql initscripts
# 25. Get general information about the bash rpm  
>> rpm -qi bash
# 26. Check if files from the pam package have changed since installation 
>> rpm -V pam
# 27. Find installed packages with "gnome" in their names 
>> yum list installed | grep gnome
# 28. Install any uninstalled package from RH Enterprise Linux CDs  
# 29. Search for Photoshop-like software, excluding Gimp 
>> yum search photoshop
# 29. Create the file /etc/yum.repos.d/cdrom.repo with appropriate content for installing from the Red Hat ISO.
# 30. Try to install any package from the new repository 
>> sudo yum install git 



#### ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------###
# admin2 lab2"

 User
# 1.	Using the useradd command, add accounts for the following users in your system: user1, user2, user3, user4, user5, user6 and user7. Remember to give each user a password.
sudo useradd user1
sudo passwd user1
sudo useradd user2
sudo passwd user2
sudo useradd user3
sudo passwd user3
# 2.	Using the groupadd command, add the following groups to your system.
Group			GID
sales			10000
hr			10001
web			10002
sudo groupadd -g 10000 sales
sudo groupadd -g 10001 hr
sudo groupadd -g 10002 web

 
# 3.	Using the usermod command to add user1 and user2 to the sales secondary group, user3 and user4 to the hr secondary group. User5 and user6 to web secondary group. And add user7 to all secondary groups  
sudo usermod -aG sales user1 user2 user7
sudo usermod -aG hr user3 user4 user7
sudo usermod -aG web user5 user6 user7

# 4.	 Login as each user and use id command to verify that they are in the appropriate groups. How else might you verify this information?
id user1
groubs user1

# 5.	Create a directory called /depts with a sales, hr, and web directory within the /depts directory.
# Create the /depts directory
sudo mkdir /depts
sudo mkdir /depts/sales
sudo mkdir /depts/hr
sudo mkdir /depts/web
ls /depts

# 6.	Using the chgrp command, set the group ownership of each directory to the group with the matching name

sudo chgrp sales /depts/sales
sudo chgrp hr /depts/hr
sudo chgrp web /depts/web

# 7.	Set the permissions on the /depts directory to 755, and each subdirectory to 770
 
sudo chmod 755 /depts
sudo chmod 770 /depts/sales
sudo chmod 770 /depts/hr
sudo chmod 770 /depts/web

# 8.	Set the set-gid bit on each departmental directory
 
sudo chmod g+s /depts/sales
sudo chmod g+s /depts/hr
sudo chmod g+s /depts/web

# 9.	Use the su command to switch to the user2 account and attempt the following commands:
# touch /depts/sales/user2.txt
# touch /depts/hr/ user2.txt
# touch /depts/web/ user2.txt
 
su user2
touch /depts/sales/user2.txt
touch /depts/hr/user2.txt
touch /depts/web/user2.txt

# 10.	Configure sudoers file to allow user3 and user4 to use /bin/mount and /bin/umount commands, while allowing user5 only to use fdisk command.
sudo visudo
user3 ALL=(ALL) /bin/mount, /bin/umount
user4 ALL=(ALL) /bin/mount, /bin/umount
user5 ALL=(ALL) /sbin/fdisk

# 11.	Login by user3 and try to unmount /boot.
sudo /bin/umount /boot
 


# 12.	Login by user4 and remount /boot. Also try to view the partition table using fdisk.
sudo /bin/mount /boot
sudo fdisk -l
user4 ALL=(ALL) /sbin/fdisk

# 13.	Create a directory with permissions rwxrwx---, grant a second group (sales) r-x permissions
mkdir testt
chmod 770 testt
sudo usermod -aG testt
chmod g=rx testt

 
# 14.	 create a file on that directory and grant read and write to a second group (sales)

 sudo groupadd sales
 chmod g+r-x testt
touch testt/file.txt
chmod g+rw testt/file.txt



# 15.	set the the owning group as the owning group of any newly created file in that directory.
chmod g+s testt
touch testt/file.txt


# 16.	Grand your colleagues a collective directory called /opt/research, where they can store generated research results. Only members of group profs and grads should be able to create new files in the directory, and new file should have the following properties:
•	the directory should be owned by root
•	new files should be group owned by group grads
•	group profs should automatically have read/write access to new files
•	group interns should automatically have read only access to new files
•	other users should not be able to access the directory and its contents at all.

sudo mkdir /opt/research
sudo chown root:root /opt/research
sudo chmod 2770 /opt/research
sudo groupadd profs
sudo groupadd grads
sudo groupadd interns
sudo chown :grads /opt/research
sudo chmod g+rw /opt/research
sudo chmod g+r /opt/research
sudo chmod o-rwx /opt/research


# 17.	Change your default SELinux mode to permissive and reboot.
sudo vi /etc/selinux/config
SELINUX=enforcing
SELINUX=permissive
sudo reboot


# 18.	After reboot, verify the system is in permissive mode.
sestatus

# 19.	 Change the default SELinux mode to enforcing.
sudo vi /etc/selinux/config
SELINUX=permissive
SELINUX= enforcing
sudo reboot

# 20.	Change the current SELinux mode to enforcing.
sudo setenforce 1

# 21.	Copy /etc/resolv.conf file to root's home directory.
sudo cp /etc/resolv.conf /root/

# 22.	 Observe the SELinux context of the intial /etc/resolv.conf
ls -Z /etc/resolv.conf

# 23.	 Move resolv.conf from root's home directory to /etc/resolv.conf
sudo mv /root/resolv.conf /etc/

# 24.	 Observe the SELinux of the newly copied /etc/resolv.conf
ls -Z /etc/resolv.conf

# 25.	 Restore the SELinux context of the newly positioned /etc/resolv.conf
sudo restorecon /etc/resolv.conf

# 26.	 Observe the SELinux context of the restored /etc/resolv.conf
ls -Z /etc/resolv.conf

# 27.	 Configure OpenSSH to allow pulic key-based login credentials
ssh-keygen -t rsa -b 2048
ssh-copy-id alaa@hostname
sudo vi /etc/ssh/sshd_config
PubkeyAuthentication yes
AuthorizedKeysFile  .ssh/authorized_keys
PasswordAuthentication no
sudo systemctl restart ssh
ssh alaa@hostname



# 28.	 Create an SSH key-pair
ssh-keygen -t rsa -b 2048

 
# 30.	 Configure SSH to prevent root logins.
sudo nano /etc/ssh/sshd_config
PermitRootLogin no
sudo systemctl restart ssh

# 31.	Configure logrotate default setting to compress log files when they are rotated
sudo nano /etc/logrotate.conf

