
# Basic Linux Commands

Here are some basic Linux commands with examples.

## 1. `pwd` – Print Working Directory
Shows the current directory you're in.
```bash
pwd
```

## 2. `ls` – List Directory Contents
Lists files and directories in the current directory.
```bash
ls
```
With options:
```bash
ls -l    # Detailed listing
ls -a    # Show hidden files
```

## 3. `cd` – Change Directory
Changes the directory.
```bash
cd /home/user/    # Go to a specific directory
cd ..             # Move one level up
cd ~              # Go to the home directory
```

## 4. `mkdir` – Make Directory
Creates a new directory.
```bash
mkdir new_directory
```

## 5. `rmdir` – Remove Directory
Deletes an empty directory.
```bash
rmdir directory_name
```

## 6. `rm` – Remove Files or Directories
Deletes files or directories.
```bash
rm file_name       # Delete a file
rm -r dir_name     # Delete a directory and its contents
```

## 7. `touch` – Create an Empty File
Creates an empty file or updates the timestamp of an existing file.
```bash
touch newfile.txt
```

## 8. `cp` – Copy Files and Directories
Copies files or directories.
```bash
cp file1.txt file2.txt       # Copy a file
cp -r dir1/ dir2/            # Copy a directory and its contents
```

## 9. `mv` – Move or Rename Files/Directories
Moves or renames files or directories.
```bash
mv oldfile.txt newfile.txt   # Rename file
mv file.txt /home/user/      # Move file to another directory
```

## 10. `cat` – Concatenate and Display Files
Displays the content of a file.
```bash
cat file.txt
```

## 11. `echo` – Display a Line of Text
Displays text or variable values.
```bash
echo "Hello, World!"
```

## 12. `man` – Manual Pages
Shows the manual page for a command.
```bash
man ls       # Manual for ls command
man echo     # Manual for echo command
```

## 13. `chmod` – Change File Permissions
Modifies the file permissions.
```bash
chmod 755 file.txt       # Set read, write, execute for owner and read, execute for others
chmod +x file.sh         # Make a script executable
```

## 14. `chown` – Change File Ownership
Changes the owner and group of a file.
```bash
chown user:group file.txt
```

## 15. `ps` – Report Process Status
Displays information about running processes.
```bash
ps           # Show processes running in the current shell
ps aux       # Show all running processes
```

## 16. `kill` – Terminate a Process
Kills a process by PID.
```bash
kill 1234    # Kill the process with PID 1234
```

## 17. `top` – Task Manager
Shows running processes and resource usage.
```bash
top
```

## 18. `df` – Disk Space Usage
Displays available disk space.
```bash
df -h       # Human-readable format
```

## 19. `du` – Disk Usage
Shows the disk usage of files and directories.
```bash
du -h file.txt     # Shows disk usage for a file
du -sh directory/  # Shows total disk usage of a directory
```

## 20. `free` – Memory Usage
Displays memory usage.
```bash
free -h      # Human-readable format
```

## 21. `ifconfig` – Network Interface Configuration
Shows network interface information (older command, replaced by `ip` in some distributions).
```bash
ifconfig
```

## 22. `ip` – Show/Manipulate Routing, Devices, and Tunnels
New command for network interfaces.
```bash
ip a        # Show all IP addresses
ip link     # Show network devices
```

## 23. `wget` – Non-Interactive Network Downloader
Downloads files from the web.
```bash
wget http://example.com/file.txt
```

## 24. `curl` – Transfer Data with URLs
Transfers data to/from a server.
```bash
curl http://example.com
curl -O http://example.com/file.txt
```

## 25. `tar` – Archive Files
Creates and extracts compressed archive files.
```bash
tar -cvf archive.tar file1 file2  # Create an archive
tar -xvf archive.tar              # Extract an archive
```

## 26. `grep` – Search Text Using Patterns
Searches for patterns in files.
```bash
grep "pattern" file.txt
grep -r "pattern" /directory     # Search recursively in a directory
```

## 27. `find` – Search Files and Directories
Search for files based on conditions.
```bash
find /path/to/search -name "*.txt"
find . -type f -size +1M        # Find files larger than 1MB
```

## 28. `history` – Command History
Displays the history of commands used.
```bash
history
```

## 29. `alias` – Create Aliases for Commands
Creates shortcuts for commands.
```bash
alias ll="ls -l"
alias update="sudo apt update"
```

## 30. `sudo` – Execute a Command as Another User (Usually root)
Executes commands with administrative privileges.
```bash
sudo apt update          # Run the update command with root privileges
sudo rm -rf /important   # Delete important files (dangerous command!)
```

# Other Linux Commands with Examples

## 1. `uname` – Print System Information
Displays system information.
```bash
uname -a         # Show detailed information about the system
uname -r         # Show the kernel version
```

## 2. `shutdown` – Shutdown or Reboot the System
Turns off or restarts the system.
```bash
shutdown now     # Shutdown immediately
shutdown -r now  # Reboot immediately
```

## 3. `reboot` – Reboot the System
Restarts the system.
```bash
reboot
```

## 4. `date` – Show the Current Date and Time
Displays the current date and time.
```bash
date
```

## 5. `who` – Who is Logged In
Shows who is logged in.
```bash
who
```

## 6. `uptime` – System Uptime
Shows how long the system has been running.
```bash
uptime
```

## 7. `env` – Show Environment Variables
Displays the environment variables.
```bash
env
```

## 8. `clear` – Clear the Terminal Screen
Clears the terminal screen.
```bash
clear
```

## 9. `exit` – Exit the Shell
Exits the current shell session.
```bash
exit
```

## 10. `sudo apt-get` – Package Management (Debian-based)
Manages packages (install, remove, update, etc.) on Debian-based distributions.
```bash
sudo apt-get update         # Update package list
sudo apt-get upgrade        # Upgrade installed packages
sudo apt-get install package_name  # Install a package
sudo apt-get remove package_name   # Remove a package
```
