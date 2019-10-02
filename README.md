# TerminalDrill_Permissions
Solutions

### Instructions

1. create a file
```
ls > test.txt
```
2. check the owner and group of the file (use ls)
```
ls -l test.txt
```
3. change its owner to root
```
sudo chown root test.txt
```
4. change its group to root
```
sudo chgrp root test.txt
```
5. check that file’s permission (use ls)
```
ls -l test.txt  
```
6. give all rights to owner and group, but none to others
```
sudo chmod 770 test.txt
```
7. try to print the file on screen
```
more test.txt
```
8. print the file with root privileges
```
sudo more test.txt
```
