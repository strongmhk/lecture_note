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


### Manipulatuin  
---  

- cp : copy files and directories  
***ex)*** $ cp adsp.pdf adp.pdf  
          $ cp -r dir1 dir2  
          
- mv : move files and directories or rename them  
***ex)*** $ mv new_module.py ../OneDrive  

- rm : delete files and directories permantely and irreversevely(cautions!)  
***ex)*** rm file1 file2  

- mkdir : make a new directory  
***ex)*** $ mkdir new_direc  

- Wildcards  
1. * : all file names  
2. a* : all file names that begin with the character "g"  
3. a*.txt : all filenames that begin with the character "b" and end with the characters ".txt"  
4. cp *.txt text_files  
5. rm *~  

-Help command  
1. help  
***ex)*** $ help cd  
2. man  
***ex)*** $ man cp  

- etc command  
exit : exit CLI  
$ exit  

---  





