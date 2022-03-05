**0-current_working_directory** - this prints the absolute path name of the current working directory
<br>
```pwd```
#
**1-listit** - this list the contents of the current directory
<br>
```ls```
#
**2-bring_me_home** - changes working directory to the user's home directory
<br>
```cd```
#
**3-listfiles** - display current directory contents in a long format
<br>
```ls -l```
#
**4-listmorefiles** - display current directory contents including hidden files
<br>
```ls -la```
#
**5-listfilesdigitonly** - display current directory contents (long format, user and group ids in number, hidden files)
<br>
```ls -lan```
#
**6-firstdirectory** - creates a directory names my_first_directory in the /temp directory
<br>
```mkdir tmp/my_first_directory```
#
**7-move the file bety from /tmp to /tmp/my_first_directory**
<br>
```mv tmp/betty tmp/my_first_directory```
#
**8-firstdelte** - delete the file betty in the directory /tmp/my_first_directory
<br>
```rm /tmp/my_first_directory/betty```
#
**9-firstdirdeletion** - delete the directory my_first_Directory that is in the /tmp directory
<br>
```rm -r \tmp\my_first_directory```
#
**10-back** - changes the working directory to the previous one.
<br>
```cd -```
#
**11-lists** - lists all files in the current directory and the parent of the working directory and the /boot directory
<br>
```ls . .. /boot```
#
**12-file_type** - prints the type of the type of the file named iamafile.
<br>
```file  /tmp/iamafile```
#
**13-symbolic_link** - create a symbolic link to /bin/ls
<br>
```alias __ls__="ls"```
#
**14-copy_html** - copy all HTML files in the current working directory to the parent directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory.(u stands for --update)
<br>
```cp -u *.html ..```
