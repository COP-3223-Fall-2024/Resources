# Guide for Incoming CS Students: Basic Linux Commands and Running Programs

## Basic Linux Commands

### Navigation and File Management
- **`pwd`**: Print Working Directory
  - Usage: `pwd`
  - Example: Displays the current directory path.
- **`ls`**: List Directory Contents
  - Usage: `ls [options] [directory]`
  - Example: `ls -l` lists files with detailed information.
- **`cd`**: Change Directory
  - Usage: `cd [directory]`
  - Example: `cd /home/user/Documents` changes the current directory to Documents.
- **`mkdir`**: Make Directory
  - Usage: `mkdir [directory]`
  - Example: `mkdir new_folder` creates a new directory named `new_folder`.
- **`rmdir`**: Remove Directory
  - Usage: `rmdir [directory]`
  - Example: `rmdir old_folder` removes the directory named `old_folder`.
- **`rm`**: Remove Files or Directories
  - Usage: `rm [options] [file/directory]`
  - Example: `rm file.txt` deletes the file `file.txt`.
  - Example: `rm -r folder_name` recursively deletes the directory `folder_name` and its contents.
- **`cp`**: Copy Files or Directories
  - Usage: `cp [options] source destination`
  - Example: `cp file1.txt file2.txt` copies `file1.txt` to `file2.txt`.
  - Example: `cp -r dir1 dir2` copies directory `dir1` to `dir2`.
- **`mv`**: Move or Rename Files or Directories
  - Usage: `mv [options] source destination`
  - Example: `mv old_name.txt new_name.txt` renames `old_name.txt` to `new_name.txt`.
  - Example: `mv file.txt /home/user/Documents` moves `file.txt` to the Documents directory.

### Viewing and Editing Files
- **`cat`**: Concatenate and Display File Contents
  - Usage: `cat [file]`
  - Example: `cat file.txt` displays the contents of `file.txt`.
- **`nano`**: Simple Text Editor
  - Usage: `nano [file]`
  - Example: `nano file.txt` opens `file.txt` for editing.
- **`vim`**: Advanced Text Editor
  - Usage: `vim [file]`
  - Example: `vim file.txt` opens `file.txt` for editing.

### File Permissions and Ownership
- **`chmod`**: Change File Permissions
  - Usage: `chmod [permissions] [file]`
  - Example: `chmod 755 script.sh` sets the permissions of `script.sh` to `755`.
- **`chown`**: Change File Ownership
  - Usage: `chown [owner][:group] [file]`
  - Example: `chown user:group file.txt` changes the owner and group of `file.txt`.

### System Information
- **`uname`**: Print System Information
  - Usage: `uname [options]`
  - Example: `uname -a` prints all system information.
- **`df`**: Display Disk Space Usage
  - Usage: `df [options]`
  - Example: `df -h` displays disk space usage in a human-readable format.
- **`free`**: Display Memory Usage
  - Usage: `free [options]`
  - Example: `free -h` displays memory usage in a human-readable format.
- **`top`**: Display Task Manager
  - Usage: `top`
  - Example: Displays real-time system statistics and active processes.

## Running Programs

### Compiling and Running C Programs
1. **Write a C Program**
   - Example: Create a file named `hello.c` with the following content:
     ```c
     #include <stdio.h>

     int main() {
         printf("Hello, World!\n");
         return 0;
     }
     ```
2. **Compile the Program**
   - Usage: `gcc [source file] -o [output file]`
   - Example: `gcc hello.c -o hello`
3. **Run the Program**
   - Usage: `./[output file]`
   - Example: `./hello`

### Running Python Programs
1. **Write a Python Program**
   - Example: Create a file named `hello.py` with the following content:
     ```python
     print("Hello, World!")
     ```
2. **Run the Program**
   - Usage: `python3 [file]`
   - Example: `python3 hello.py`

### Running Java Programs
1. **Write a Java Program**
   - Example: Create a file named `HelloWorld.java` with the following content:
     ```java
     public class HelloWorld {
         public static void main(String[] args) {
             System.out.println("Hello, World!");
         }
     }
     ```
2. **Compile the Program**
   - Usage: `javac [source file]`
   - Example: `javac HelloWorld.java`
3. **Run the Program**
   - Usage: `java [class name]`
   - Example: `java HelloWorld`

### Running Shell Scripts
1. **Write a Shell Script**
   - Example: Create a file named `hello.sh` with the following content:
     ```sh
     #!/bin/bash
     echo "Hello, World!"
     ```
2. **Make the Script Executable**
   - Usage: `chmod +x [file]`
   - Example: `chmod +x hello.sh`
3. **Run the Script**
   - Usage: `./[file]`
   - Example: `./hello.sh`

## Conclusion

Learning these basic Linux commands and understanding how to run programs will help you become more proficient and comfortable in a Unix-like environment. Practice these commands regularly to build your confidence and enhance your skills.
