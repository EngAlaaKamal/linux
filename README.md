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
## to verify ##
1- Create a directory
mkdir directory
ls -l mydirectory
2- Create a file
touch file.txt
ls -l myfile.txt
 {
 


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
Execute (x) Permission on a File:
For a file, the "x" permission means the ability to execute the file as a program. It allows the user to run the file if it contains executable code.
For a script or program file, the execute permission is necessary for it to be executed.
For a Directory:
Execute (x) Permission on a Directory:
For a directory, the "x" permission means the ability to access (enter) the directory and execute certain operations within the directory.
Without the execute permission on a directory, you cannot access its contents or navigate into it.

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



