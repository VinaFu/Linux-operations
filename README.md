# Linux-operations

add:

redicrect - pipeline

grep: search
"Grep is an acronym that stands for Global Regular Expression Print.
Grep is a Linux / Unix command-line tool used to search for a string of characters in a specified file."

grep phoenix sample2：（“phoenix” in the file sample2）
grep phoenix sample sample2 sample3：（“phoenix” in the file smaple, sample2, sample3）



1. 现在位置：pwd 

2. 清单：ls
      
      ls -a: show every file, even the hidden files, also readable or not
      ls -l: permission of holder file and group, everyone else
      [drwxr] - delete, read, write, excute 

3. mkdir - make directory

      mkdir dir1 - create one directory

4. cd - go the place

       cd .. - back home
       cd ~/dir2 - home=~/

5. clear - clear the ternimal

6. touch - create a file

   (dir1)$ touch file.text - create a file in dir1
   
7. nano -editor, 
     
     ctrl + x - escape
     y - save
     
8. cat file1.txt -show/see content

   less file1.txt -  long content, to see the end
   q- exit
   
9. mv - rename
      
      mv file1.txt file2.txt -file1 change into file2
 
10. cp - copy

    cp file2.txt file1.txt -copy file2 and name it file1
    cp file1.txt ~/dir2/file1.txt  -copy file to another place
    cd .. -exit this page
    cd dir2  -go to dir2
    
11. rm -remove (forever)

      rm file -remove file, direct
      rmdir dir2 -remove directory, but the directory must be empty
      or
      rm -R dir2 -remove directory without limitations

12. which -file/folder's location

      which mongod
      /usr/bin/...
      
13. history -show your command

14. sudo - run as rootuser

 ----   system command ----  
 
15. config

      ifConfig -ip address, local address, loopback..
      
      iwconfig -wireless config

16.  ping - ping device? pther network, machine

     ping fgdj.com - unknow host
     ping google.com 
     ctrl + c - exit
     
17. uname -a

      operation system version, like your(computer's) name

18. blkid - show hard drive
    
19. top -process, memory, cpu

      system monitor -do the same 
      q -exit

20. df -available and unavailable space

21. lsusb -usb

22. lspci ....

23. sudo apt-get install filezilla -download

    sudo apt-get remove filezilla -delete the device

24. sudo apt-get update -just update 

25. sudo shutdown -h now/10 minutes  - shutdown 
