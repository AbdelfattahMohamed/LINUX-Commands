# LINUX Commands

Hello everone, Let's see LINUX commands...

[My GITHUB](https://github.com/AbdelfattahMohamed)

> COMMANDS FOR LINUX DEBIAN, UBUNTU, ....

| Command | Description | Example |
| --- | --- | --- |
| $ | for user | _ |
| # | for Admin | _ |
| ls | list of folders & files | _ |
| ls l | list of folders & files  "long format"| _ |
| cd .. | up which means back to the sub folder | _ |
| cd home | cd directory | cd home/xFile/zFile|
| clear | clear terminal | |
| cd - | back which means back to last folder | _ |
| shift +pageUP | to up to the first terminal | _ |
| shift +pageDown | to up to the end terminal | _ |
| CTRL + R | Search in history by typing first character | more |
| !char | give me last command start with f or this char | !f |
| command -h  | for get help about this command | _ |
| command --help | for get help about this command  | _ |
| man command | for get help about this command  | _ |
| info command | for get help about this command  | _ |
| man -k copy | Return all command that include copy | _ |
| man -k "copy files" | Return all command that include copy | _ |
| file fileName | Return Info about file or folder | file sample.txt |
| cat fileName | Return any values inside the file | cat sample.txt |
| head fileName | Returrn first 10 lines  | head sample.tx |
| tail fileName | Return last 10 lines | tail sample.txt |
| more fileName | Return a new terminal with more information about the file | "You can show more by press space btn |
| less fileName | Return a new terminal with less information about the file | _ |
| cp sample1.txt folder/sample2.txt | Copy file sample1 in folder with name sample2  | _ |
| nv sample1.txt folder/sample1.txt | Move file sample1 to folder with name sample1| _ |
| nv sample1.txt sample2.txt | Rename file sample1 to sample2| _ |
| rm sample1.txt | Remove file or folder | _ |
| mkdir | make directory "folder" | _ |
| rmdir | remove directory "folder" | _ |
| cp -avr directory1 directory2 | a for save attributes, v for copy all in the directory & r for creating the file  | _ |

> some Issues & commands
> we assume we have a directory include "test1,test2,test3,test11,test111" 

| Command | Return | Notes |
| --- | --- | --- |
| test* | test1,test2,test3,test11,test111 | _ |
| test? | test1,test2,test3 | ? return one char after test word |
| test?? | test11 | _ |
| test??? | test111 | _ |
| test[1-2] | test1,test2 | _ |
| test[1,3] | test1,test3 | _ |
| ls>file.txt | Overwrite the run of this command "ls" in file file.txt | _ |
| ls>>file.txt | Append the run of this command "ls" in file file.txt | _ |
| ls|more | instead of run ls only , run ls and put the run as input to more | name of "|" PIPE|
| ; | if i want to write more than command in the same line | _ |
| command1 && command2 | if command1 fail,command2 be fail | _ |
| command1 & | command1 run normal and you can use the terminal in other something| _ |
| which command | means "where this command" | which ls |
| where | means "where this command" & more details | _ |
| lcoate Name | Search & Return pathes include this name| EX:"locate firefox" __File System__|
| find Name | Search & Return pathes include this name | __My files__ |
| ps | Return the Programs is running | _ |
| w | Return users whose logged in | _ |
| id | Return info like id, name & more details about users | _ |
| df | Return file system disk space | _ |
| du | Return Disk Usuage | _ |
| top | Return like task manager | _ |
| free | Return Memory,free | _ |
| cat /proc/ecuinfo | Return some info about CPU | _ |
| cat /proc/meminfo | Return some info about memory | _ |
| uname -a | Return the name of the machine | _ |
| gcc fileName.c | RUN __C program__ | _ |
| gcc fileName1.c -o test.out | Run C program and i want to rename the output file | _ |

Regards, __@Abdelfattah Mohamed__
