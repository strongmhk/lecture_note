# Lecture_note  

### Shell commands  
---
- pwd : shows the **current path** in a directory  
***ex)*** $ pwd  
          /c/Users/kim65  
          
- cd : change directory  
***ex)*** $ cd OneDrive  
          kim65@DESKTOP-JS2CS9H MINGW64 ~/OneDrive  
          $ cd ..   -> upper-level directory   
          
  ***ex)*** $ pwd  
          kim65@DESKTOP-JS2CS9H MINGW64 ~/OneDrive  
          $ cd ..  
          /c/Users/kim65  
          
- ls : list files and directories  
***ex)*** $ ls  
          '3D Objects'/ AppData/ 'Application Data'@  
           Contacts/ Cookies@  Documents/  
           Downloads/   ELibrary/   Favorites/  
           
- arguments   
[directory name]/(root) : argument of directory  
***ex)*** $ cd OneDrive/OSS  
. : current directory  
.. : upper-level directory 
~ : home of current user    
/[directory name] : absolute path  
./[directory name] : relative path  
../[directory name] : relative path  

- options of ls  
$ ls -l : detail information of files or directories (long format)  
$ ls -lh : displays the size of the file in kilobytes.
***ex)*** -rw-rwr--1  minh  minh  576  Apr  17  2022  imp.txt  
 (file permissions) (owner) (group)  (size)  (modification time)  (file name)  
 
 'up arrow' key : copy the previous command  
 tab key : autocomplete names of files in a directory  
 
---
