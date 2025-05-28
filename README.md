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

**Output:** ![Screenshot 2025-05-28 193628](https://github.com/user-attachments/assets/f4c4203e-9c6f-44bc-bdc5-5ead80f78ead)


### 2. `pwd` Command

The `pwd` command displays the location of the current working directory.

**Syntax:**
```bash
pwd
```

**Output:** ![Screenshot 2025-05-28 193706](https://github.com/user-attachments/assets/6b690a66-a0b4-49a8-9084-0d35e60f8ff0)


### 3. `mkdir` Command

The `mkdir` command is used to create a new directory.

**Syntax:**
```bash
mkdir <directory_name>
```

**Output:** ![Screenshot 2025-05-28 193742](https://github.com/user-attachments/assets/8b6a803d-a0b7-4cc0-bc98-7906af589adc)


### 4. `rmdir` Command

The `rmdir` command is used to delete a directory.

**Syntax:**
```bash
rmdir <directory_name>
```

**Output:** ![Screenshot 2025-05-28 193809](https://github.com/user-attachments/assets/fc2016c4-65c8-4cbf-ab17-ceb5035e6919)


### 5. `cd` Command

The `cd` command is used to change the current directory.

**Syntax:**
```bash
cd <directory_name>
```

**Output:** ![Screenshot 2025-05-28 193835](https://github.com/user-attachments/assets/a8592377-da1f-4078-93fd-1acb1b2958f6)


### 6. `cat` Command

The `cat` command is used to create, display, and concatenate files.

**Syntax:**
```bash
cat [OPTION]... [FILE]...
```

**Output:** ![Screenshot 2025-05-28 193920](https://github.com/user-attachments/assets/a9e1cad8-758b-4973-8803-d247936b258f)


### 7. `cp` Command

The `cp` command is used to copy files or directories.

**Syntax:**
```bash
cp <source_file> <destination_file>
```

**Output:** ![Screenshot 2025-05-28 193949](https://github.com/user-attachments/assets/a5af7eb1-40a1-4b85-83ce-84709cf01093)


### 8. `gedit` Command

`gedit` is a general-purpose text editor used to create and edit text files.

**Syntax:**
```bash
gedit <file_name>
```

**Output:** ![Screenshot 2025-05-28 194040](https://github.com/user-attachments/assets/47c196fe-124a-491c-8712-8daeb5f4f6ec)


### 9. `su` Command

The `su` command provides administrative access to another user.

**Syntax:**
```bash
su <username>
```

**Output:** ![Screenshot 2025-05-28 194104](https://github.com/user-attachments/assets/a4b2563d-9246-43fa-af98-3682b5b7488d)


### 10. `mv` Command

The `mv` command is used to move a file or directory from one location to another.

**Syntax:**
```bash
mv <file_name> <directory_path>
```

**Output:** ![Screenshot 2025-05-28 194133](https://github.com/user-attachments/assets/043264b9-6011-4984-8dab-9c8412202fdb)


### 11. `rename` Command

The `rename` command is used to rename files.

**Syntax:**
```bash
rename 's/old-name/new-name/' <files>
```

**Output:** ![Screenshot 2025-05-28 194225](https://github.com/user-attachments/assets/42008f39-da9e-4843-b4a5-f7271b8d2b7c)


### 12. `head` Command

The `head` command displays the first 10 lines of a file.

**Syntax:**
```bash
head <file_name>
```

**Output:** ![Screenshot 2025-05-28 194259](https://github.com/user-attachments/assets/5d9614fa-a4fb-4c86-964f-f219516001b3)


### 13. `tail` Command

The `tail` command displays the last 10 lines of a file.

**Syntax:**
```bash
tail <file_name>
```

**Output:** ![Screenshot 2025-05-28 194339](https://github.com/user-attachments/assets/9d744fe6-37ea-4f7e-b5c7-5da87d205f52)


### 14. `id` Command

The `id` command displays the user ID (UID) and group ID (GID).

**Syntax:**
```bash
id
```

**Output:** ![Screenshot 2025-05-28 194412](https://github.com/user-attachments/assets/6d9e922f-21b2-436e-8681-b73b24c8e443)


### 15. `grep` Command

The `grep` command is used to search for a pattern within files.

**Syntax:**
```bash
command | grep <search_word>
```

**Output:** ![Screenshot 2025-05-28 194441](https://github.com/user-attachments/assets/afa56ef1-feee-4582-a779-b36d1a3c5213)


### 16. `tr` Command

The `tr` command is used to translate or delete characters.

**Syntax:**
```bash
command | tr <old> <new>
```

**Output:** ![Screenshot 2025-05-28 194518](https://github.com/user-attachments/assets/da1782c1-c201-4e53-b9cc-d018bbe6241a)


### 17. `chmod` Command

The `chmod` command is used to change the access mode (permissions) of a file.

**Syntax:**
```bash
chmod <options> <permissions> <file_name>
```

**Output:** ![Screenshot 2025-05-28 194551](https://github.com/user-attachments/assets/045efeb0-12d7-4a08-9950-3ddf03fb18f2)


### 18. `tar` Command

The `tar` command is used to create or extract archive files.

**Syntax:**
```bash
tar [options] [archive-file] [files_to_archive]
```

**Output:** ![Screenshot 2025-05-28 194619](https://github.com/user-attachments/assets/09d7ef39-659a-4a38-a1de-2d930f4ba55a)


### 19. `chown` Command

The `chown` command is used to change the ownership of a file.

**Syntax:**
```bash
chown <owner_name> <file_name>
```

**Output:** ![Screenshot 2025-05-28 194646](https://github.com/user-attachments/assets/c58045e3-de94-43a7-9f4e-652075a91f6c)


### 20. `make` Command

The `make` command is used to build and maintain groups of programs.

**Syntax:**
```bash
make [-f makefile] [options] [targets]
```

**Output:** ![Screenshot 2025-05-28 194710](https://github.com/user-attachments/assets/c63e8c8a-a43a-4f0c-a367-f2d566973755)


### 21. `ifconfig` Command

The `ifconfig` command is used to configure network interfaces.

**Syntax:**
```bash
ifconfig [options] [interface]
```

**Output:** ![Screenshot 2025-05-28 194737](https://github.com/user-attachments/assets/b0d60e28-7eba-4bbc-9c40-12673014d998)


### 22. `chmod 777` Command

The `chmod 777` command gives read, write, and execute permissions to the owner, group, and others.

**Syntax:**
```bash
chmod 777 <file_name>
chmod -R 777 /path/to/file/or/folder
```

**Output:** ![Screenshot 2025-05-28 211634](https://github.com/user-attachments/assets/81876f1c-06e9-4839-a454-7a6745fb24f3)


### 23. `host` Command

The `host` command is used to display the IP address for a given domain name.

**Syntax:**
```bash
host <domain_name> or <ip_address>
```

**Output:** ![Screenshot 2025-05-28 211700](https://github.com/user-attachments/assets/fdf06bdb-1ea2-4c38-90c4-e13df65b9d1c)


### 24. `gzip` Command

The `gzip` command is used to compress files, replacing the original file with a compressed one with a `.gz` extension.

**Syntax:**
```bash
gzip <file1> <file2> <file3>...
```

**Output:** ![Screenshot 2025-05-28 211723](https://github.com/user-attachments/assets/c4d6d394-8fe1-4b8f-9c85-d640aaf35c63)


### 25. `sort` Command

The `sort` command is used to sort the contents of a file alphabetically.

**Syntax:**
```bash
sort <file_name>
```

**Output:** ![Screenshot 2025-05-28 211822](https://github.com/user-attachments/assets/7f0dd9cf-bb3f-4e79-a5bf-3e6ce74125d9)


### 26. `cal` Command

The `cal` command displays the current month's calendar with the current date highlighted.

**Syntax:**
```bash
cal
```

**Output:** ![Screenshot 2025-05-28 211850](https://github.com/user-attachments/assets/f9c056d9-550c-4413-89d9-b2789162b180)


### 27. `clear` Command

The `clear` command clears the terminal screen.

**Syntax:**
```bash
clear
```

**Output:** ![Screenshot 2025-05-28 211912](https://github.com/user-attachments/assets/e3624ecb-76b2-45e2-8846-96ab5a7dc02d)


### 28. `mail` Command

The `mail` command is used to send emails from the command line.

**Syntax:**
```bash
mail
```

**Output:** ![Screenshot 2025-05-28 211936](https://github.com/user-attachments/assets/deaf4418-0b87-4388-8fed-fa478deec524)


### 29. `df` Command

The `df` command displays the disk space usage of file systems.

**Syntax:**
```bash
df
```

**Output:** ![Screenshot 2025-05-28 211959](https://github.com/user-attachments/assets/fea5f092-9030-40a3-979a-97a7e1c8227b)


### 30. `find` Command

The `find` command is used to search for files in a directory hierarchy.

**Syntax:**
```bash
find <directory> -name <file_name>
```

**Output:** ![Screenshot 2025-05-28 212023](https://github.com/user-attachments/assets/cdefa7c5-f599-4631-af82-629715e608f6)


## Result
Linux commands are executed in the linux terminal successfully.
