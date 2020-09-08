# Bash examples
## ls
 * ls: Print a short list of files.
 * ls my*: Print a long list of files of the previous directories.
 * ls my?dir: Print the content that is in my directory.
 * ls my*dir*: Print all the files of the previous directories.

## cp
 * cp file 1 file 2: Copy the first file to another file.
 * cp -i*.txt: Copy in the previous directory all the text files.
 * cp -R dir1 dir2: Copy the directory 1 to the directory 2. It is important to use -R which means Recursive.
 * cp -R/direction/destination: Copy the absolute direction where we are.

## locate
 * locate word: Localize in all the directories files with this word.
 * 

## find
 * find . -name "filename": search the document with this name.
 * find . -atime +number: search the documents that have been modified or created in the directory in the time.
 * find / -name *.extension: search all the documents with this extension.
 * find / -name *.extension .fprint filenametoprint: search and send output from the find command to a file.
 * find /home -iname namefile: find files using name and ignoring cases
 * find / -type d -name filename: Find directories using name.
### Find exercise
 * find . -name scorers.txt
 * find /home -iname scorers.txt
 * find . -atime +20
 * find / -type d -name Aymimadre
 * find . -type f -name ".txt"

## whoami
 * whoami: Show the user

## id
 * id: show more informtion about the user.

## groups
 * groups: show the groups of the computer.

## stat
 * stat filename: see all the netadata of a file

## chmod
 * chmod +x filename: give permission to the execution of the program.
 * chmod -x filename: quit permission to the execution of the program.
 * chmod 0numbersofheinsruction filename: cahnge permission to the execution of the program.
    * --- 0
    * --x 1
    * -w- 2
    * -wx 3
    * r-- 4
    * r-x 5
    * rw- 6
    * rwx 7
