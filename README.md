# **Common Command Line Commands in Linux**

## **Print working directory** 
### **``pwd``**
This is helpful to list the full path to your current working directory. Most people are familiar with the graphical program managers that have folder icons/pictures and their respective files. A directory in the command line is similar to what a folder is in the graphical program managers. A current working directory lists all the folders opened to access the current folder.

## **Change directory**
### **``cd``** 
Opens another directory. If your current working directory is /home/jeff and you would like to change to /home/jeff/Documents, typing: **``cd /home/jeff/Documents``** will open the Documents folder. A faster way to accomplish this is to type **``cd Documents``** 

## **List files/folders**
### **ls**
This will list the files and directories inside a current working directory. Helpful if you want to **``cd``** (change) to another directory. For example if there are two directories named **``word_docs``** and **``text_files``** inside the **``Documents``** directory, and you are currently at **``/home/jeff/Documents``** the **``ls``** command will list **``word_docs``** and **``text_files``**


## **Change to your ``/home/user`` directory``** 
### **``cd``** 
If you are at **``/home/jeff/Documents/word_docs``** 
**``cd``** will change you to **``home/jeff``**

## **Change to the upstream directory**
### **``cd ..``** 
If you are at **``/home/jeff/Documents/word_docs``** 
**``cd ..``** will change you to **``/home/Jeff/Documents``**

## **Delete a file**
### **``rm -rf "filename"``**
Type the filename without the quotes.You must be in the directory of the file you wish to delete or you can type the full path.
