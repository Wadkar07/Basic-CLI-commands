# Basic-CLI-commands
## 1.pwd
```bash
$ pwd
```
```pwd``` prints the name of the working directory
## 2. cd
```bash
$ cd Desktop/
```
```cd``` takes a directory name as an argument, and switches into that directory.
```bash
$ cd Desktop/New Folder
```
To navigate directly to a directory, use ```cd``` with the directory’s path as an argument. Here, ```cd Desktop/New Folder/``` command navigates directly to the Desktop/New Folder directory.
## 3. cd ..
```bash
$ cd ..
```
To move up one directory, use ```cd ..```. Here, ```cd ..``` navigates up from Desktop/New Folder/ to Desktop/.
## 4. ls
```bash
$ ls
```
```ls``` lists all files and directories in the working directory
## 5. ls -a
```bash
$ ls -a
```
```ls -a``` lists all contents in the working directory, including hidden files and directories
## 6. ls -l
```bash
$ ls -l
```
```ls -l``` lists all contents of a directory in long format.
## 7. ls -t
```bash
$ ls -t
```
```ls -t``` orders files and directories by the time they were last modified.
## 8. mkdir
```bash
$ mkdir media
```
```mkdir``` takes in a directory name as an argument, and then creates a new directory in the current working directory. Here we used mkdir to create a new directory named media/.
## 9. touch
```bash
$ touch data.txt
```
```touch``` creates a new file inside the working directory. It takes in a file name as an argument, and then creates a new empty file in the current working directory. Here we used touch to create a new file named sample.txt inside the Desktop/New Folder/.
## 10. rm
```bash
$ rm data.txt
```
```rm``` deletes files. Here we remove the file data.txt from the current directory.
## 11. rm -r
```bash
$ rm -r New Folder
```
rm -r deletes a directory and all of its child directories.
## 12. gedit
```bash
$ gedit <filename>
```
```gedit``` is a file editor where you can edit your text document and save. you can exit the editor by typing ```ctrl+x```
