# linux-commands

### 1. Navigating the File System

#### `pwd` (Print Working Directory)
Displays the current directory you are in.
```sh
pwd
```

#### `ls` (List Directory Contents)
Lists files and directories in the current directory.
```sh
ls
```

- `ls -l`: Lists files in long format (detailed view).
- `ls -a`: Includes hidden files (those starting with a dot).

#### `cd` (Change Directory)
Changes the current directory to the specified directory.
```sh
cd /path/to/directory
```

- `cd ..`: Moves up one directory.
- `cd ~`: Moves to the home directory.

### 2. File Operations

#### `touch` (Create a New File)
Creates an empty file with the specified name.
```sh
touch filename
```

#### `cp` (Copy Files or Directories)
Copies files or directories.
```sh
cp source destination
```

- `cp -r source_directory destination_directory`: Recursively copies directories.

#### `mv` (Move/Rename Files or Directories)
Moves or renames files or directories.
```sh
mv source destination
```

#### `rm` (Remove Files or Directories)
Deletes files or directories.
```sh
rm filename
```

- `rm -r directory`: Recursively deletes a directory and its contents.
- `rm -i filename`: Asks for confirmation before deleting each file.

#### `mkdir` (Make Directory)
Creates a new directory.
```sh
mkdir directory_name
```

#### `rmdir` (Remove Directory)
Removes an empty directory.
```sh
rmdir directory_name
```

### 3. Viewing and Editing Files

#### `cat` (Concatenate and Display Files)
Displays the contents of a file.
```sh
cat filename
```

#### `nano` (Text Editor)
Opens a text file in the `nano` text editor.
```sh
nano filename
```

#### `less` (View File Contents)
Views the contents of a file one screen at a time.
```sh
less filename
```

### 4. System Information

#### `uname` (System Information)
Displays system information.
```sh
uname -a
```

#### `df` (Disk Space Usage)
Shows disk space usage.
```sh
df -h
```

#### `top` (Task Manager)
Displays real-time system information, including running processes.
```sh
top
```

### 5. Managing Processes

#### `ps` (Process Status)
Displays information about running processes.
```sh
ps aux
```

#### `kill` (Terminate Process)
Terminates a process by its PID (Process ID).
```sh
kill PID
```

- `kill -9 PID`: Forcefully kills a process.

### 6. Permissions

#### `chmod` (Change File Permissions)
Changes file or directory permissions.
```sh
chmod permissions filename
```

#### `chown` (Change File Owner)
Changes the ownership of a file or directory.
```sh
chown user:group filename
```

### 7. Networking

#### `ping` (Check Network Connection)
Checks the network connection to a host.
```sh
ping hostname
```

#### `ifconfig` (Network Interface Configuration)
Displays or configures network interfaces (requires root permissions).
```sh
ifconfig
```
