# Common Command Line Commands

> **``pwd``**

**Print working directory** This is helpful to list the full path to your current working directory. Most people are familiar with graphical program managers (folder icons/pictures and their respective files). A directory in the command line is similar to what a folder is in the graphical program managers. A current working directory lists all the folders opened to access the current folder you have open.

> **``cd``** 

**Change directory** Opens another directory. Example: if your current working directory is /home/jeff and you would like to change to /home/jeff/Documents, typing: **``cd /home/jeff/Documents``** will open the Documents folder. A faster way to accomplish this is to type **``cd Documents``** Typing ``cd /Documents`` will not work. If you want to type the **``/``** character you will need to include the full path name **``cd /home/jeff/Documents``** Alternatively, if you know there is a directory named **``word``** inside the **``Documents``** directory **and** you are currently at /home/jeff, you can use the **``/``** character by typing **``cd "FullPathName"``** (without the quotes) or as a shortcut **``cd Documents/word``**

>**ls**

**List files/folders**

This will list the files and directories inside a current working directory. Helpful if you want to cd (change) to another directory. For example if your current working directory home/jeff/
cd ) Change to your home directory. (J home/jeff)?)
(cd ../) Change to upstream? Directory. If you are at home/jeff/Documents (cd ../) will change you to home/Jeff
(How to update your packages and receive security updates) If you're using Ubuntu, Ubuntu will automatically download security updates (not sure about non-security package updates). (sudo apt-get update) followed by (sudo apt-get upgrade). Any command that begins with sudo apt-get can be shortened to sudo apt if you're using Ubuntu 16 or later. You can think of the (sudo apt-get update) as updating the list of pending package/security updates and the (sudo apt-get) as actually installing the updates. Linux will ask you to type Y to confirm the updates. 
(rm -rf (filename)) Deletes file name. You must be in the directory of the file you wish to delete or you can type the full path if you're not in that file’s directory. 
(dpkg -l) List all your packages. Helpful to get the exact package name if you want to delete a package.
((exact package name) autoremove --purge) The --purge part of the command is optional. If you include the purge it will remove the package as well as dependencies not required by any other program/packages)
