# Exercises to practice the usage of a few basic Linux commands

Via the following exercises we would learn to use the commands: 
```mkdir``` , ```cp``` , ```mv``` , ```ls``` and ```rm```.

## Brief documentation of the command
### copying files and directories (cp)<br>
cp: to copy files or folders from SOURCE to DESTINATION (DEST).<br>
syntax:<br>
cp \[SOURCE\] \[DEST\] (this will not copy folders)<br>
cp **-r** \[SOURCE\] \[DEST\] (this will copy files as well as folders)<br>
*one needs to replace SOURCE and DEST with the actual file or directory names.*<br>
examples:<br>
```cp ~/Documents/work_report.txt .``` --> this will copy the file *work_report.txt* located in the Documents folder of HOME to the current location. <br>
```cp ../pdfs/new_article.pdf important/article2.pdf``` --> this will copy the file *new_article.pdf* from the directory pdfs located one level higher than the current location (thus the ```../```). It will copy it to another directory *important* located in the current location and also change the name to *article2.pdf*<br>
```cp -r ../all_papers old_paper/``` --> this will copy the directory *all_papers* along with all its contents to the folder *old_paper* located in the current location.
```cp -r ../all_papers new_papers``` --> this will copy the directory *all_papers* located a level higher than the current working directory to the current directory and also change its name to new_papers. Notice the presence of ```/``` at the end is important.

### moving files and directories (mv) <br>
mv: to move files or folders from SOURCE to DEST.
syntax:<br>
mv \[SOURCE\] \[DEST\] (this will not copy folders)<br>
mv **-r** \[SOURCE\] \[DEST\] (this will copy files as well as folders)<br>
*one needs to replace SOURCE and DEST with the actual file or directory names.*<br>
The examples and usage are similar to ```cp```.

## to show the contents of a directory or the current working directory (ls):<br>
ls: to show the contents of directories<br>
syntax:<br>
ls (shows the contents of the current directory)<br>
ls \[PATH\] (shows the contents to the directory located at \[PATH\]<br>
examples:<br>
```ls```<br>
```ls ../``` --> this shows the contents of the directory a level higher<br>
```ls ../reports/``` --> this shows the contents of the directory *reports* located a level higher<br>
```ls new_reports/``` --> this shows the contents of the directory *new_reports* located at the current directory<br>

## to create a new directory (mkdir):<br>
mkdir: to create a new directory<br>
syntax:<br>
mkdir \[PATH\]/\[directory name\] (create a new directory at the specified \[PATH\]<br>
examples:<br>
```mkdir dir1``` --> create a directory name *dir1* at the current location<br>
```mkdir ~/Documents/new_dir``` --> create a directory named *new_dir* in the directory *Documents* location at HOME (```~/```)<br>
```mkdir dir1/dir2``` --> creates a directory named *dir2* inside the already existing directory *dir1*<br>

## to remove folders and files (rm):<br>
rm: to remove files and folders/directories<br>
syntax:<br>
rm \[PATH\] (this will not remove/delete folders)<br> 
rm -r \[PATH\] (this will delete folders as well as files)<br>
examples:<br>
```rm new_code.cpp``` --> removes a file called *new_code.cpp* from the current location.<br>
```rm ../new_code.cpp``` --> removes a files called *new_code.cpp* located a level higher in the directory tree.<br>
```rm -r dir1``` --> removes a directory *dir1* from the current location.<br>
```rm -r dir1/dir2``` --> removes the directory *dir2* inside *dir1*. it will not delete *dir1*<br>

 
