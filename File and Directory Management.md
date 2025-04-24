# File & Directory Creation:

## touch:
Touch command is used to create files. Using touch command, multiple files can be created. 
### Syntax:
    touch <filename>

- Creating file in current directory.

      touch file1.txt

- Creating file in desired directory.

      touch /root/file1.txt

- Creating multiple file at different locations.

      touch /root/Desktop/file1.txt /etc/data.mp3

- Creating multiple files at same location but with different file names (below example will create 3 files. You can add more file names and separate them by coma).

      touch /root/{data.txt,file.txt,demo.mp3}

- Creating multiple files having continuous number in their names (below example will create hundred files with name starting from file1 to file100.) 

      touch /root/file{1..100}.txt
  
    
### mkdir:
Mkdir command creates directories. Creating multiple directories are also possible using mkdir command.
### Syntax: 
    mkdir <option> <path/directory_name> 

- Creating directory in / directory.

       mkdir /dir1

- Creating multiple directories.

      mkdir /dir1 /root/Desktop/dir2 /etc/demo 
      mkdir /root/{demo,data,practice} 
      mkdir /practical{1..10}

- Creating parent directory if it is not exist.

      mkdir –p /demo/data/practice
  

# File Read Operations:
# Copy, Move & Rename:
# Deleting Files & Directories
# Redirectors:

