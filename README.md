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