# Terminal

## Task for terminal lesson

[link to full list](https://app.monstercampaigns.com/c/jg9u9k0by4lj9pvcjeso/)

### Linux commands

1. **pwd** - to get full adress of directory you´re in
2. **cd** - change directory (subdirectory == just a name; another directory == full path)
   * ¨..¨ up
   * ¨cd¨ home folder
   * ¨-¨ previous dir
3. **ls** - list of contents of directory (working or enter full adress)
    * ¨-r¨ all files in dir+subdir
    * ¨-a¨ hidden files
    * ¨-al¨ with detailed info
4. **cat** - concatenate - to get contents of file and list them in terminal
   * ¨> filename¨ create a new file
   * ¨filename1 filename2>filename3¨ joins two files (1 and 2) and stores the output of them in a new file (3)
   * ¨filename | tr a-z A-Z >output.txt¨ to convert a file to upper or lower case
5. **cp** - to copy files from current directory to (cp filename /adress)
6. **mv** - to move files (filename /adress) or rename (oldname.ext newname.ext)
7. **mkdir** - make directory inside another (Music/**Newdir**) or
   * ¨-p¨ - make a dir between two dir-s (-p Music/**2020**/Newdir) 
8. **rmdir** - to delete _empty_ dir-s, to check use ¨ls -a¨ 
9. **rm** - to delete dir
   * ¨-r¨ - to delete dir
10. **touch** - to create file (/home/username/Documents/Web.html)
11. **locate** - to find file 
    * ¨-i¨ to make it case-insensitive; * - btw parts of name (-i school*note)
12. **find** - to search for files
13. **grep** - to search for a text in given file (blue notepad.txt)
14. **sudo** - superuser**do**
15. **df** - to report about disk space in KB
    * ¨-m¨ - in MB
16. **du** - to check how much space is taken
    * ¨-h¨ - in bytes/kb-s/mb-s
17. **head** - to view first 10 lines in text file; to show 5 lines 4-ex. (-n 5 filename.ext.)
18. **tail** - same but last 10 lines
19. **diff** - to compare files and show what doesn´t match (file1.ext file2.ext)
20. **tar** - to archive multiple files (rather complex command)
21. **chown** - to change owner of file (linuxuser2 filename.ext)
22. **jobs** - to display all jobs running in the shell
23. **kill** - to terminate programm that failed to respond (options in the article)
24. **ping** - to ping site (google.com); ctrl+c - to stop
25. **wget** - to download files (link)
26. **uname** - detailed info about system
27. **top** - list of running processes
28. **history** - to show history of commands entered
29. **man** - to show manual of command (tail) 
30. **echo** - to add text in file (Hello, my name is Hello>> readme.txt)
31. **unzip** - to extract files
32. **hostname** - to know the name of network
    * ¨-i¨ to show ip
33. **useradd; userdel** - to add or delet user
34. **clear** - to clear terminal


_tab_ == autofill

_ctrl+c_ - to stop command; _+z_ - to pause
_ctrl+s_ - freeze terminal; _+q_ unfreeze
_ctrl+a_ - to the beginning of the line; _+e_ to the end