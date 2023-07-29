# Getting-into-Kali-Linux

## Navigating through Linux system

### Printing the current working directory
To check the current working directory use command **_pwd_** which means print working directory.

```bash
pwd

/home/dipon/Desktop
```

### Listing all the files and folders of the current working directory

To print all the contents of the current working directory use command **_ls_**.

```bash
ls

```

### Changing the current working directory

To change the current working directory use command **_cd_**.

```bash
pwd

/home/dipon/Desktop

cd ..

/home/dipon

ls

Desktop  Downloads Documents

cd Downloads

pwd

/home/dipon/Downloads
```

### Creating and Managing FIles

### Creating files

**Command:** _touch filename_

```bash
touch myfile.txt
```

### Printing contents of the file
**Command:** _cat filename_

```bash
cat myfile.txt
```

### Writing contents into the file
**Command:** _echo (message to be written) > filename_

```bash
echo my name is Dipon > myfile.txt
cat myfile.txt

my name is Dipon
```

### Making directories
**Command:** _mkdir foldername_

```bash
ls

file1 file2.txt file3.py

mkdir new_folder

ls

file1 file2.txt file3.py new_folder
```

### Moving files
**Command:** _mv filename_to_be_moved foldername/directory_path_where_the_file_move

```bash
ls

file1 file2.txt file3.py

mkdir new_folder

ls

file1 file2.txt file3.py new_folder

mv file3.py new_folder

ls

file1 file2.txt new_folder

cd new_folder

ls

file3.py
```

### Copying files
**Command:** _cp filename_of_the_file_to_be_copied new_filename_

(Same as command _mv_)

```bash
ls

file1 file2.txt file3.py new_folder

cp file3.py file4.py

ls

file1 file2.txt file3.py file4.py new_folder
```