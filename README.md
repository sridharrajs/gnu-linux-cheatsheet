# gnu-linux-cheatsheet

A bunch of things to get by quickly in GNU/Linux

## File manager

|Description|Command|
|-----------|-------|
|Restarting the file manager|`pkill nautilus && nohup nautilus 2> /dev/null &`|

# Terminal

## Status
|Description|Command|
|-----------|-------|
|Print current working directory location| `pwd`|

## Navigation - Filesystem
|Description|Command|
|-----------|-------|
|Go to home| `cd ~`|
|Go to previous location before navigation| `cd -`|
|Change directory to folder| `cd <folder_name>`|
|List all the items within a directory| `ls -alh`,  `a` => all items including hidden, `l` => display as a list `h`=> human readable format for the file size.|

## Files & Folder

|Description|Command|
|-----------|-------|
|Create a file| `touch <file_name_with_extn>`|
|To see the content of a file| `cat <file_name>`|
|Create a folder| `mkdir <folder_name>`|
|Create a folder and navigate to it| `mkdir <folder_name> && $$_`|

## Search

| Description | Command |
|-------------|---------|
| Seach file | `find . <path> -name <filename-with-extenstion>`, `.` is to search in nested folder |

## Cut, Copy & Paste
|Description|Command|
|-----------|-------|
| Cut | `Ctrl` + `Shift` + `X`|
| Copy | `Ctrl` + `Shift` + `C`|
| Paste | `Ctrl` + `Shift` + `V`|

## Text Manipulation

|Description|Command|
|-----------|-------|
|Move to the beginning of the text| `Ctrl` + `A`|
|Move to the end of the text| `Ctrl` + `E`|
|Kill rest of the line, when in somewhere midway of the text| `Ctrl` + `K`|
|Clear line| `Ctrl` + `U`|
|Clear terminal|`Ctrl` + `L`|

