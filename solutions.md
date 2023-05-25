# Solutions to the exercises<br>
### ** there could be more than a single solution. The answers represent only one of the solutions.<br>

## Exercise-1<br>
```mkdir dir1
cd dir1
touch file1.txt
cd
cd dir1/
mkdir dir2
cd dir2/
cp ../file1.txt .
rm file1.txt 
mkdir dir3
cd dir3/
cp ../../file1.txt .
cd ../../
touch file2.txt
ls
rm file2.txt 
cd dir2/
rm -r dir3/
cd ..
mkdir dir4
touch file4.txt
cd dir4/
cp ../file4.txt .
cd
rm -r dir1```
