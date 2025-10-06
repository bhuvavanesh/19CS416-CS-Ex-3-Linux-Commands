
# 19CS416-CS-Ex-3-Linux-Commands

**Linux** is an open-source operating system, and its kernel is the heart of the OS, facilitating communication between hardware and software. One of the key advantages of Linux is its customizability; developers can modify the Linux kernel to create their own tailored operating systems.

## Linux Commands

Linux commands are executed in the terminal, which is case-sensitive. This guide covers some basic and advanced commands used in Linux.

### 1. `ls` Command

The `ls` command is used to display a list of contents in a directory.

**Syntax:** 
```bash
ls
```

**Output:**

<img width="438" height="82" alt="image" src="https://github.com/user-attachments/assets/b4ef5d63-295d-4346-9042-a557c59581b5" />




### 2. `pwd` Command

The `pwd` command displays the location of the current working directory.

**Syntax:**
```bash
pwd
```

**Output:**

<img width="637" height="75" alt="image" src="https://github.com/user-attachments/assets/d77543ca-ac37-4ac6-a2b3-c7673c2ac1aa" />



### 3. `mkdir` Command

The `mkdir` command is used to create a new directory.

**Syntax:**
```bash
mkdir <directory_name>
```

**Output:**


<img width="610" height="124" alt="image" src="https://github.com/user-attachments/assets/19c14168-7e1f-444d-9824-7f8abc3ad44d" />



### 4. `rmdir` Command

The `rmdir` command is used to delete a directory.

**Syntax:**
```bash
rmdir <directory_name>
```

**Output:**


<img width="601" height="61" alt="image" src="https://github.com/user-attachments/assets/6d2eb717-470a-4f36-b177-6476e1bd5cec" />


### 5. `cd` Command

The `cd` command is used to change the current directory.

**Syntax:**
```bash
cd <directory_name>
```

**Output:**


<img width="598" height="88" alt="image" src="https://github.com/user-attachments/assets/7f88a31a-a719-449e-9bb5-51ac1b1391c1" />


### 6. `cat` Command

The `cat` command is used to create, display, and concatenate files.

**Syntax:**
```bash
cat [OPTION]... [FILE]...
```

**Output:**



<img width="607" height="165" alt="image" src="https://github.com/user-attachments/assets/4e624c82-943b-414c-bfef-98833f7c973a" />



### 7. `cp` Command

The `cp` command is used to copy files or directories.

**Syntax:**
```bash
cp <source_file> <destination_file>
```

**Output:**

<img width="628" height="160" alt="image" src="https://github.com/user-attachments/assets/5eafc013-62cb-411c-b4e0-cb090dafda6c" />



### 8. `gedit` Command

`gedit` is a general-purpose text editor used to create and edit text files.

**Syntax:**
```bash
gedit <file_name>
```

**Output:**



<img width="240" height="42" alt="image" src="https://github.com/user-attachments/assets/bda1b41a-2e38-4ebb-bc21-2d0f07bb1795" />


### 9. `su` Command

The `su` command provides administrative access to another user.

**Syntax:**
```bash
su <username>
```

**Output:**

<img width="302" height="148" alt="image" src="https://github.com/user-attachments/assets/4c11bd17-5630-41e3-b87e-84ae6e5b0acc" />



### 10. `mv` Command

The `mv` command is used to move a file or directory from one location to another.

**Syntax:**
```bash
mv <file_name> <directory_path>
```

**Output:**


<img width="377" height="322" alt="image" src="https://github.com/user-attachments/assets/e4430b25-cf7c-41db-b88d-05a1a4d4c0e8" />



### 11. `rename` Command

The `rename` command is used to rename files.

**Syntax:**
```bash
rename 's/old-name/new-name/' <files>
```

**Output:**

<img width="316" height="58" alt="image" src="https://github.com/user-attachments/assets/49395f39-c5d7-46b5-9a80-f8d3c3df4680" />


### 12. `head` Command

The `head` command displays the first 10 lines of a file.

**Syntax:**
```bash
head <file_name>
```

**Output:**


<img width="426" height="202" alt="image" src="https://github.com/user-attachments/assets/ce0de74a-b229-400a-ac41-4a2ef4207aff" />



### 13. `tail` Command

The `tail` command displays the last 10 lines of a file.

**Syntax:**
```bash
tail <file_name>
```

**Output:**

<img width="425" height="185" alt="image" src="https://github.com/user-attachments/assets/1d5375ee-26e7-4530-8662-fdda336eec2a" />


### 14. `id` Command

The `id` command displays the user ID (UID) and group ID (GID).

**Syntax:**
```bash
id
```

**Output:**


<img width="1116" height="80" alt="image" src="https://github.com/user-attachments/assets/19864db2-a293-427f-9a52-bc2824369297" />


### 15. `grep` Command

The `grep` command is used to search for a pattern within files.

**Syntax:**
```bash
command | grep <search_word>
```

**Output:**

<img width="416" height="78" alt="image" src="https://github.com/user-attachments/assets/9b9c23aa-a531-4366-b2f5-a35c17103a44" />



### 16. `tr` Command

The `tr` command is used to translate or delete characters.

**Syntax:**
```bash
command | tr <old> <new>
```

**Output:**


<img width="442" height="223" alt="image" src="https://github.com/user-attachments/assets/65bb05f2-7169-4c18-81bc-a1c512d98275" />


### 17. `chmod` Command

The `chmod` command is used to change the access mode (permissions) of a file.

**Syntax:**
```bash
chmod <options> <permissions> <file_name>
```

**Output:**

<img width="242" height="52" alt="image" src="https://github.com/user-attachments/assets/aff918ec-dfa8-4694-a7ce-8f1f6b4aa1f7" />



### 18. `tar` Command

The `tar` command is used to create or extract archive files.

**Syntax:**
```bash
tar [options] [archive-file] [files_to_archive]
```

**Output:**

<img width="343" height="78" alt="image" src="https://github.com/user-attachments/assets/7006140e-77a7-4506-864e-0e841af610ae" />



### 19. `chown` Command

The `chown` command is used to change the ownership of a file.

**Syntax:**
```bash
chown <owner_name> <file_name>
```

**Output:**

<img width="306" height="50" alt="image" src="https://github.com/user-attachments/assets/0597dd1a-d95a-4cf2-8a91-a8f2ce5cd293" />


### 20. `make` Command

The `make` command is used to build and maintain groups of programs.

**Syntax:**
```bash
make [-f makefile] [options] [targets]
```

**Output:**

<img width="382" height="176" alt="image" src="https://github.com/user-attachments/assets/027151d2-4ff5-4d54-8b12-bc808b0b5462" />


### 21. `ifconfig` Command

The `ifconfig` command is used to configure network interfaces.

**Syntax:**
```bash
ifconfig [options] [interface]
```

**Output:**
<img width="707" height="415" alt="image" src="https://github.com/user-attachments/assets/6966d214-91c8-48c6-998e-51ae51b6b9a1" />




### 22. `chmod 777` Command

The `chmod 777` command gives read, write, and execute permissions to the owner, group, and others.

**Syntax:**
```bash
chmod 777 <file_name>
chmod -R 777 /path/to/file/or/folder
```

**Output:**



<img width="262" height="56" alt="image" src="https://github.com/user-attachments/assets/3b768661-6cee-443c-8bff-40797ae9e100" />

### 23. `host` Command

The `host` command is used to display the IP address for a given domain name.

**Syntax:**
```bash
host <domain_name> or <ip_address>
```

<img width="702" height="220" alt="image" src="https://github.com/user-attachments/assets/6636fafb-3986-4187-9e1e-c5f4d149e459" />


**Output:**

### 24. `gzip` Command

The `gzip` command is used to compress files, replacing the original file with a compressed one with a `.gz` extension.

**Syntax:**
```bash
gzip <file1> <file2> <file3>...
```

**Output:**


<img width="536" height="227" alt="image" src="https://github.com/user-attachments/assets/cbe945dd-ab62-4855-adfd-022f9d7298c3" />


### 25. `sort` Command

The `sort` command is used to sort the contents of a file alphabetically.

**Syntax:**
```bash
sort <file_name>
```

**Output:**


<img width="457" height="332" alt="image" src="https://github.com/user-attachments/assets/8babf8bc-dbd0-4b03-a07a-4db314a6963d" />


### 26. `cal` Command

The `cal` command displays the current month's calendar with the current date highlighted.

**Syntax:**
```bash
cal
```

**Output:**


<img width="222" height="162" alt="image" src="https://github.com/user-attachments/assets/77bdb57b-4d38-4065-97dd-1f5507bed238" />


### 27. `clear` Command

The `clear` command clears the terminal screen.

**Syntax:**
```bash
clear
```

**Output:**


<img width="237" height="55" alt="image" src="https://github.com/user-attachments/assets/bd59c6d7-83b0-4feb-97a0-3afe091eb2a2" />


### 28. `mail` Command

The `mail` command is used to send emails from the command line.

**Syntax:**
```bash
mail
```

**Output:**

<img width="606" height="116" alt="image" src="https://github.com/user-attachments/assets/57da8f61-7d94-49fd-b18e-e1c75ac9f91c" />



### 29. `df` Command

The `df` command displays the disk space usage of file systems.

**Syntax:**
```bash
df
```

**Output:**


<img width="562" height="182" alt="image" src="https://github.com/user-attachments/assets/a53fec41-c79a-44e7-9d2b-97d1c60a2306" />


### 30. `find` Command

The `find` command is used to search for files in a directory hierarchy.

**Syntax:**
```bash
find <directory> -name <file_name>
```

**Output:**


<img width="435" height="206" alt="image" src="https://github.com/user-attachments/assets/4dde978e-db36-492b-b9ac-ac4a31b9897c" />

## Result

Linux commands are executed in the linux terminal successfully.

