# Exercises to practice the usage of a few basic Linux commands

Via the following exercises we would learn to use the commands: 
```mkdir``` , ```cp``` , ```mv``` , ```ls``` and ```rm```.

## Brief documentation of the command
### copying files and directories (cp)<br>
cp: to copy files or folders from SOURCE to DESTINATION (DEST).<br>
syntax: cp SOURCE DEST (this will not copy folders)<br>
        cp **-r** SOURCE DEST<br>
*one needs to replace SOURCE and DEST with the actual file or directory names.*<br>
examples:<br>
```cp ~/Documents/work_report.txt .``` --> this will copy the file *work_report.txt* located in the Documents folder of HOME to the current location. <br>
```cp ../pdfs/new_article.pdf important/article2.pdf``` --> this will copy the file *new_article.pdf* from the directory pdfs located one level higher than the current location (thus the ```../```). It will copy it to another directory *important* located in the current location and also change the name to *article2.pdf*<br>
```cp -r ../all_papers old_paper/``` --> this will copy the directory *all_papers* along with all its contents to the folder *old_paper* located in the current location.

 
