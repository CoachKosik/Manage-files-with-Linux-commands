# Manage files with Linux commands

## Objective

This project focuses on enhancing file organization and security within a Linux environment. By leveraging fundamental Linux commands, the goal is to optimize directory structures and file permissions to maintain data integrity and accessibility.

## Project description

This project involved managing and organizing a Linux file system. By utilizing basic Linux commands, the goal was to restructure a directory, create new directories, move files, and edit file contents. This exercise aimed to enhance skills in file system navigation, file operations, and text editing, which are essential for effective system administration and cybersecurity tasks.

## Skills Learned

* **File System Navigation:** Using commands like `cd` to navigate between directories.
* **File and Directory Manipulation:** Employing commands like `mkdir`, `rmdir`, `mv`, and `rm` to create, remove, and move files and directories.
* **File Editing:** Using a text editor like `nano` to create and modify files.
* **Basic Linux Commands:** Understanding and utilizing fundamental commands like `ls`, `pwd`, and `cat` to list files, display the current directory, and view file contents.

By mastering these skills, effective management and organization of files within a Linux environment can be achieved, essential for various tasks, including system administration, software development, and cybersecurity.

## Tools Used

* **Linux Terminal:** The primary tool used to interact with the Linux system and execute commands.
* **Basic Linux Commands:** Commands like `mkdir`, `rmdir`, `mv`, `rm`, `cd`, `ls`, and `nano` were used to create, remove, move, and edit files and directories.

## Steps
1. Create a new directory

   1. Create a new subdirectory called logs in the /home/analyst directory.
   2. List the contents of the /home/analyst directory to confirm that you’ve successfully created the new logs subdirectory.
      
2. Remove a directory

   1. Remove the /home/analyst/temp directory.
   2. List the contents of the /home/analyst directory to confirm that you have removed the temp subdirectory.
  
3. Move a file

   1. Navigate to the /home/analyst/notes directory.
   2. Move the Q3patches.txt file from the /home/analyst/notes directory to the /home/analyst/reports directory.
   3. List the contents of the /home/analyst/reports directory to confirm that you have moved the file successfully.

4. Remove a file

   1. Remove the tempnotes.txt file from the /home/analyst/notes directory.
   2. List the contents of the /home/analyst/notes directory to confirm that you’ve removed the file successfully.

5. Create a new file

   1. Use the touch command to create an empty file called tasks.txt in the /home/analyst/notes directory.
   2. List the contents of the /home/analyst/notes directory to confirm that you have created a new file.<br>
![manage linux files 1](https://github.com/user-attachments/assets/5d1c567e-e77a-4f90-a84c-2680e4c21331)
 <br>

6. Edit a file

   1. Using the nano text editor, open the tasks.txt file that is located in the /home/analyst/notes directory.
   2. Copy and paste the following text into the text input area of the nano editor:
       *   Completed tasks
       *   Managed file structure in /home/analyst<br>
![manage linux files 2](https://github.com/user-attachments/assets/38136966-7bc6-411a-b6af-f12d8b36c012)<br>
       <br>
   3. Press CTRL+X to exit the nano text editor.<br>
  ![manage linux files 4](https://github.com/user-attachments/assets/87cd7ab8-eb5a-4792-b898-8da4706c70ab)<br>

   4. Press Y to confirm that you want to save the new data to your file. (Answering "no" will discard changes.)
   5. Press ENTER to confirm that File Name to Write is tasks.txt.
   6. Use the clear command to clear the Bash shell window and remove any traces of the nano text input area.
   7. Display the contents of the tasks.txt file to confirm that it contains the updated task details.<br>
![manage linux files 4](https://github.com/user-attachments/assets/9103302d-a520-4f97-8647-8427f393a764)
<br>

### Summary

This lab focuses on fundamental Linux file system management tasks. By using commands like mkdir, rmdir, mv, and rm, users can create, delete, and move directories and files. The nano text editor is employed to create and edit text files. These tasks are essential for organizing and maintaining a clean and efficient file structure, a crucial skill for system administrators and security analysts.
