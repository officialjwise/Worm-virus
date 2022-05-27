# Worm-virus
Worm is type of malware that replicates itself and other files to consume spaces in our hard drives.
You may find your drives or partitions get full without any visible reason and that might happen because of a worm.
A Worm virus is different from a computer Virus.
Typical viruses only infects files.
Worms replicates files and keep the duplicates out of sight (as hidden files).
We will need two modules to write a worm virus in python.
Here, os is the most important module.
We will utilize it to list all files and directories alongside retrieving the absolute paths.
Shutil is used to copy file contents.
There are obviously other ways to do it, however, I chose to do it using shutil.copyfile() method.
I have commented each line of code for better understanding.
