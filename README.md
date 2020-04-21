# Linux

# System information
> ip addr  (NOTE: ipconfig is deprecated.)


# Remoting
Putty - always use the installer version. Standlone will not work. Choose SSH option and port 22.

# References
https://youtu.be/4P23_rhyTgc

# Touch
> touch zzz{1..10}.txt  to generate multiple files with a pattern

# File system navigation
> cd -   ( to go back to previous visited directory)
> cd ~ (home directory)
> cd /   (root directory)
> mkdir -p parent/child/sub-child (to generate directory hierarchy)
> mkdir -p parent/{child1,child2,...} (no spaces after comma)
> rmdir <directory_name>
> rmdir -pv <directory_structure> ('v' for verbose)
> rm -rf <directory_name>
> cp -pi <file1> <file2> <destination_directory> (option 'p' to preserve the timestamp of original file. option 'i' warns before overwriting)
> cp <old_file_name> <new_file_name>
> cp -R <directory1> <directory2> (recursive copy. if the destination not present, new directory is created. otherwise, a new sub-directory with contents of source is copied to destination)
> ls -a (to list hidden files and directories. Files prefixed with a dot.)
> ls -ltr (to list files in long format sorted by timestamp latest first)
> ls -d (only directories)
> ls -R (to see whole directory hierarchical structure)

# Searching files
> grep
> find
sort

# Peek
> cat <file_name>
> cat > <file_name> (to write to text to file)
> cat >> <file_name> (to append text to file at the end)
> cat <file1> <file2> <output_file>   (concatenates the content and writes to 3rd file)

# Users, groups and privileges
sudo
su

# File permissions
> chown
> chgrp
> chmod

# Scripting
> echo $SHELL (to find out the default scripting. BASH is the most common one)

# Aliasing
> alias lx = "ls -lX"

# References
> man <command_name>

# Questions
root user vs super user??
how to sort listing of files by extension, timestamp, name and then by size?
command to look at log files and tail those logs?
sudo vs su?
how to merge two directories?
