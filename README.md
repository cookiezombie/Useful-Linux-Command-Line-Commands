# **Common Commands in the Linux Command Line**
Learning how to use the command line can open up a whole new world. Even knowing a few basic commands can allow you to perform useful tasks. Plus, all your friends will be impressed with your new "hacker" skills!  
 
When we open up a terminal session we see something like:
>**`jeff@localhost:~$`**  

`jeff@localhost:~$` is called a shell prompt and lists your username (jeff) and the name of your linux machine (mine is named localhost). The shell prompt is the first thing we see Whenever we open up the terminal. We start typing our commands at the end of the shell prompt after the $ symbol.  

## **Print working directory** 
### **`pwd`** 
Typing **`pwd`** into the terminal     
>**`jeff@localhost:~$ pwd`**  

returns:  
>**`/home/jeff`**      

This is like the "you are here" symbol on a map. It returns your current location on your Linux system. Most people are familiar with the graphical program file managers with it's icons/pictures of folders that open up more folders/files upon clicking them. A directory is similar to what a folder is in the graphical program file managers. The location returned by typing pwd is known as the current working directory. A current working directory lists all the folders that are open. Here the current working directory is `/home/jeff`. It's helpful to know your current working directory just like it's good to know where your position is on a map. You can use your current working directory to help you move to another directory or perform another activity like saving a file to the correct location. 

## **Change directory**
### **``cd``** 
Changes your location in Linux. This will open another directory, similar to double-clicking on a folder in a graphical program file manager. If your current working directory is /home/jeff and you would like to change to /home/jeff/Documents, typing: **``cd /home/jeff/Documents``** will open the Documents folder. A faster way to accomplish this is to type **``cd Documents``** Here's an example:

> **`jeff@localhost:~$ pwd`** &nbsp; &nbsp; &nbsp; (Type pwd to get your current working directory)  
> **`/home/jeff`** &nbsp; &nbsp; &nbsp; (Linux returns your current working directory)  
> **`jeff@localhost:~$ cd Documents`** &nbsp; &nbsp; &nbsp; (Type cd Documents to change your location)  
> **`jeff@localhost:~/Documents$`** &nbsp; &nbsp; (The shell prompt is updated with your new location, the Documents directory)

Linux returns your new location with a ~ symbol to abbreviate the entire path/location before Documents.   

## **List files/folders**
### **``ls``**
This is like looking at a map and wondering what's inside a location. The **`ls`** command will list the files and directories inside the current working directory. We can use this information to **``cd``** (change) to another directory. Here's an example:

>**`jeff@localhost:~/Documents$ ls`** (Type ls to see the files/folders inside Documents)  
 
>**`word_docs`** **`text_files`** (Linux returns the names of two folders inside Documents) 
 
>**`jeff@localhost:~/Documents$ cd word_docs`** (Type cd word_docs to change directory)

>**`jeff@localhost:~/word_docs$`** (Linux shell prompt updates with your new current working directory)


## **Shortcut to change to your ``/home/user`` directory** 
### **``cd``** 
When the terminal first opens, we see this:  
>**`jeff@localhost:~$`**  

The default current working directory when we first start the terminal is **`/home/user`**. Since my user name is jeff, mine would be /home/jeff. If I start the terminal and change my current directory /home/jeff/Documents/word_docs, I can change back to /home/jeff by typing **`cd /home/jeff`**. A shortcut to do this would be to simply enter **`cd`**.

>**`jeff@localhost:~/word_docs$ cd`** (Type cd to change to /home/user directory)
>**`jeff@localhost:~$`** (Linux returns to the /home/user directory)  

## **Change to the upstream directory**
### **``cd ..``** 
If you are at **``/home/jeff/Documents/word_docs``**  

**``cd ..``** will change you to **``/home/Jeff/Documents``**

>**`jeff@localhost:~/word_docs$ cd ..`** (Type "cd ..". Use a space after the cd. No spaces between the periods.)
  
>**`jeff@localhost:~/Documents$`** (Back to the Documents directory)


## **Delete a file**
### **``rm -rf filename``**
You must be in the directory of the directory/file you wish to delete or you can type the full path.

>**`jeff@localhost:~/Documents$ ls`** (Type ls to see the directories/files inside Documents)  
 
>**`word_docs`** **`text_files`** (Two directories inside)  

>**`jeff@localhost:~/Documents$ rm -rf word_docs`** (Delete the directory named word_docs)

>**`jeff@localhost:~/Documents$ ls`** (Type ls to see if the directory was sucessfully deleted) 

>**`text_files`** (word_docs was deleted since text_files is the only directory to display.)

