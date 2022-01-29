# Lab1 Report - how to log into a course-specific account on ieng6

## Installing VScode
* Go to Website [VScode](https://code.visualstudio.com/)
* Follow the steps to download VScode.
* Install VScode on your computer.

You will get a page like this when you successfully install VScode:

![15lab1_1](https://user-images.githubusercontent.com/97651152/149599479-36860c75-4c85-484a-a169-93aea8811b5c.png)


## Remotely Connecting
* Install OpenSSH if your system is windows: [ssh Installing](https://docs.microsoft.com/en-us/windows-server/administration/openssh/openssh_install_firstuse)
* Check your course-specific account:[Account checking](https://sdacs.ucsd.edu/~icc/index.php)
* Ready to remotely connecting using vscode like this:
![15lab1_2](https://user-images.githubusercontent.com/97651152/149599453-a2f357f6-1ce8-47a9-a2ab-cabfb8114122.png)

## Trying Some Commands
You can try any commands to see how them work. Or try these commands to see how they give different results:
* ls
* ls -a
* ls -lat
* ls <directory>

![15lab1_3](https://user-images.githubusercontent.com/97651152/149599780-47e45206-23e9-4db8-a368-15634cd45681.png)

## Moving Files with scp
* Create a file on your computer: 15lab1_4.txt
* Using the scp command to move the file your created to your account:
  - scp 15lab1_4.txt cs15lwi22aoz@ieng6.ucsd.edu:~/
  
![15lab1_4](https://user-images.githubusercontent.com/97651152/149601409-7ae67afe-a565-46f4-a3e8-ef43e86c444b.png)

## Setting an SSH Key
Following the steps to set SSH keys so you do not need to enter password when you enter your account or try to move file between your account and your computer.
* ssh-keygen
  
![15lab1_5](https://user-images.githubusercontent.com/97651152/149602396-8a9f9de4-aa26-4f52-ba0d-c64903b39358.png)
Once you succeed, you will not need to enter password to login your account on this computer.
![15lab1_5](https://user-images.githubusercontent.com/97651152/149600496-7a4ea41a-4796-480c-a1c3-37180676c250.png)

## Optimizing Remote Running
Now use what you learn to optimizing remote running.Try this:
  $ ssh cs15lwi22aoz@ieng6.ucsd.edu "ls"
* See what happens!
![15lab1_6](https://user-images.githubusercontent.com/97651152/149601589-1f8c13ce-05c1-4b17-b8b1-64f73146a6bd.png)
We can use semicolons to run multiple commands, also, we can use upper arrow key to recall the last command.
 Try to use twice upper arrow key and once enter key. Which is total 3 keystrokes:
![15lab1_61](<img width="647" alt="Screen Shot 2022-01-28 at 16 41 36" src="https://user-images.githubusercontent.com/97651152/151639948-52b297f9-ece3-4531-ac20-58b7df30c401.png">
)

