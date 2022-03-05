**0-current_working_directory** - this prints the absolute path name of the current working directory
\n
```pwd```
#
**1-listit** - this list the contents of the current directory
\n
```ls```
#
**2-bring_me_home** - changes working directory to the user's home directory
```cd```
**3-listfiles** - display current directory contents in a long format
```ls -l```
**4-listmorefiles** - display current directory contents including hidden files
```ls -la```
**5-listfilesdigitonly** - display current directory contents (long format, user and group ids in number, hidden files)
```ls -lan```
**6-firstdirectory** - creates a directory names my_first_directory in the /temp directory
```mkdir tmp/my_first_directory```
**7-move the file bety from /tmp to /tmp/my_first_directory**
```mv tmp/betty tmp/my_first_directory```
**8-firstdelte** - delete the file betty in the directory /tmp/my_first_directory
```rm /tmp/my_first_directory/betty```
**9-firstdirdeletion** - delete the directory my_first_Directory that is in the /tmp directory
```rm -r \tmp\my_first_directory```
**10-back** - changes the working directory to the previous one.
```cd -```
