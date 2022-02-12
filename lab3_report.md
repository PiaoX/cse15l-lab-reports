# Lab3 Report - Streamline ssh Configuration

## .ssh/config file
* Create a .ssh/config file
![iamge](https://user-images.githubusercontent.com/97651152/153692260-6654294e-5d46-4a6f-9009-560b74ddf03c.png)

* Inside the file, we can edit it like:

   Host nameofHost
   
       HostName nameofHostName
       
       User yourOwnUsername
       
For Example, To log into ieng6, we can do this:
![iamge](https://user-images.githubusercontent.com/97651152/153691924-2f981291-83a0-480f-8f7b-fc4800770cae.png)


## ssh command
* Try ssh command:
ssh nameofHost

* You will successfully log in the username you just set:
![iamge](https://user-images.githubusercontent.com/97651152/153691933-1f00d044-038a-42f6-8bea-306b4f522c98.png)

## scp command
* Try scp command:
scp filetocope hostYouChoose

* You will copy the file to the server simply and quickly:

![iamge](https://user-images.githubusercontent.com/97651152/153691911-f4a2e805-97df-4aff-a396-51b115530602.png)


