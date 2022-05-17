---
name: Rahad kabir
class: cis 106
semester: spring 22
---
# Command name 
`date`
## Description
Display time
## Syntax
`cmd + option + time`
## Example
* Description of example:
  * `date --date="2 day"`

# Command name
`uname`
## Description
Print certain system information.
## Syntax
`uname + [option]`
## Example
* Description of example:
  * `uname -a`
* Description of example:
  * `uname -s`

# Command name
`du`
## Description
Summarize disk usage of the set of FILEs, recursively for directories.
## Syntax
`du + options +file`
## Example
* Description of example:
  * `du -h`
* Description of example:
  * `du -h *`

# Command name
`free`
## Description
Displays the total amount of free and used amount of memory.
## Syntax
`free + options`
## Example
* Description of example:
  * `free -m`
* Description of example:
  * `free -h`

# Command name
`echo`
## Description
shows the the specified text
## Syntax
`echo + option + string + variable`
## Example
* Description of example:
  * `echo 'hello world`
* Description of example:
  * `echo 'Linux user'`

# Command name
`apt`
## Description
apt is a commandline package manager and provides commands for
searching and managing as well as querying information about packages.
It provides the same functionality as the specialized APT tools,
like apt-get and apt-cache, but enables options more suitable for
interactive use by default.
## Syntax
`sudo + apt + install + package name`
## Example
* Description of example:
  * `sudo apt install firefox flamrshot caaffine -y`
* Description of example:
  * `sudo apt remove firefox flamrshot caaffine`

# Command name
`pwd`
## Description
Print the name of the current working directory.
## Syntax
`pwd + options`
## Example
* Description of example:
  * `pwd`
* Description of example:
  * `pwd -L`

# Command name
`cd`
## Description
Change the shell working directory.
## Syntax
`cd + options + directory`
## Example
* Description of example:
  * `cd Documents`
* Description of example:
  * `cd /home/username/Documents`

# Command name
`ls`
## Description
List information about the FILEs (the current directory by default).
## Syntax
`ls + options + file`
## Example
* Description of example:
  * `ls Pictures/`
* Description of example:
  * `ls -a`

# Command name
`tree`
## Description
list or display the contant of a directory in a tree format
## Syntax
`tree + options`
## Example
* Description of example:
  * `tree`
* Description of example:
  * `tree -a`

# Command name
`man`
## Description
Display user manual of any command
## Syntax
`man + options + command`
## Example
* Description of example:
  * `man mkdir`
* Description of example:
  * `command here`

# Command name
`mkdir`
## Description
it is used for creating directory
## Syntax
`mkdir + options + directory to make`
## Example
* Description of example:
  * `mkdir newDirectory`
* Description of example:
  * `mkdir newDirectory new directory2`

# Command name
`touch`
## Description
Update  the  access  and modification times of each FILE to the current time. create file.
## Syntax
`touch + option +file`
## Example
* Description of example:
  * `touch Downloads/pic`
* Description of example:
  * `touch newwallpaper_{a..e}`

# Command name
`rm`
## Description
This  manual  page  documents  the  GNU version of rm.  rm removes each specified file.  By default, it does not remove directories.
## Syntax
`rm + option + file`
## Example
* Description of example:
  * `rm -r filename`
* Description of example:
  * `rm -v filename`

# Command name
`cp`
## Description
Copy SOURCE to DEST, or multiple SOURCE(s) to DIRECTORY.
## Syntax
`cp + options + source + directory`
## Example
* Description of example:
  * `cp file file_backup`
* Description of example:
  * `cp file.txt /backup`

# Command name
`mv`
## Description
Rename SOURCE to DEST, or move SOURCE(s) to DIRECTORY.
## Syntax
`mv + options + source + directory`
## Example
* Description of example:
  * `mv file1 /ulg`
* Description of example:
  * `mv dir1 dir2`

# Command name
`stat`
## Description
 Display file or file system status.
## Syntax
`stat + options + file`
## Example
* Description of example:
  * `stat users.txt`
* Description of example:
  * `stat -f /boot`

# Command name
`wildcards` 
## Description
symbols or special characters that represent other characters.
## Syntax
`(*)([])(?)`
## Example
* Description of example:
  * `ls -l l*`
* Description of example:
  * `ls users-0*`

# Command name
`Brace expansion`
## Description
Brace expansion is a useful tecnique lists of strings that can be used in scripts and aliases .
## Syntax
`cmd + options`
## Example
* Description of example:
  * `mkdir -p assets/{imgs,video}/{large,small}`
* Description of example:
  * `mkdir -p wallpaper/cars/{1080p,2k,4k}`

# Command name
`cat`
## Description
Concatenate FILE(s) to standard output.
## Syntax
`cat + options + file`
## Example
* Description of example:
  * `cat -s file.txt`
* Description of example:
  * `cat -n /etc/lsb-releaase`

# Command name
`head`
## Description
 Print  the  first  10 lines of each FILE to standard output.  With more than one FILE, precede each with a header giving the file name.
## Syntax
`head + options + file`
## Example
* Description of example:
  * `head filename.txt`
* Description of example:
  * `head -30 filename.txt`

# Command name
`tail`
## Description
 Print  the  last  10  lines of each FILE to standard output.  With more than one FILE, precede each with a header giving the file name.
## Syntax
`tail + options + file`
## Example
* Description of example:
  * `tail filename.txt`
* Description of example:
  * `tail -n 50 filename.txt`

# Command name
`cut`
## Description
Print selected parts of lines from each FILE to standard output.
## Syntax
`cut + options + file`
## Example
* Description of example:
  * `cut test.txt -f 1,3`
* Description of example:
  * `cut test.txt -f -4`

# Command name
`tr`
## Description
Translate, squeeze, and/or delete characters from standard input, writing to standard output.
## Syntax
`tr + options + set1 + set2`
## Example
* Description of example:
  * `echo 'linuxize' | tr 'lin' 'red'`
* Description of example:
  * `echo 'linuxize' | tr 'lmno' 'wxyz'`

# Command name
paste
## Description
Write  lines  consisting  of  the sequentially corresponding lines from each FILE, separated by TABs, to standard output.
## Syntax
`paste + options + file`
## Example
* Description of example:
  * `paste file1 file2`
* Description of example:
  * `paste file1 file2 > file3`

# Command name
`wc`
## Description
Print newline, word, and byte counts for each FILE, and a total line if more than one FILE is specified.  A word is a non-zero-length  sequence of characters delimited by white space.
## Syntax
`wc + options + file`
* Description of example:
  * `wc /proc/cpuinfo /proc/meminfo`
* Description of example:
  * `wc < /proc/cpuinfo`

# Command name
`grep`
## Description
 grep  searches  for  PATTERNS  in  each  FILE.  PATTERNS is one or more patterns separated by newline characters, and  grep  prints  each line that  matches a pattern.  Typically PATTERNS should be quoted when grep is used in a shell command.
## Syntax
`grep + options + pattern + file`
## Example
* Description of example:
  * `grep bash /etc/passwd`
* Description of example:
  * `grep "gnome Display Manager" /etc/passwd`

# Command name
output redirection
## Description
Redirection is a featurein Linux such that when executing a command, you can change the standard input/output devices.
## Syntax
`ls + options`
## Example
* Description of example:
  * `la -al > listing`
* Description of example:
  * `cat mucic.mp3 > /dev/audio`

# Command name
`vim`
## Description
Vim  is a text editor that is upwards compatible to Vi.  It can be used to edit all kinds of plain text.  It is especially useful  for  editing programs.
## Syntax
`vim + options + file`
## Example
* Description of example:
* `vim file`
* Description of example:
  * ``

# Command name
`tar`
 GNU tar is an archiving program designed to store multiple files  in  a single file (an archive), and to manipulate such archives.  The archive can be either a regular file or a device (e.g. a tape drive, hence  the name  of the program, which stands for tape archiver), which can be lo‐cated either on the local or on a remote machine.
## Syntax
`tar + options + file`
## Example
* Description of example:
  * `cvf file.tar *.c`
* Description of example:
  * `tar xvf file.tar`

# Command name
`xz`
## Description
xz compress a file
## Syntax
`cmd + options`
## Example
* Description of example:
  * `ls -lh clearos-DVD-x86_64.iso`
* Description of example:
  * `xz clear-DVD-x86_64.iso`

# Command name
`chmod`
## Description
This manual page documents the GNU version of chmod.  chmod changes the file mode bits of each given file according to mode, which can  be either a symbolic representation of changes to make, or an octal number representing the bit pattern for the new mode bits.
## Syntax
`chmod + options + mode +mode +file`
## Example
* Description of example:
  * `chmod g=r filename`
* Description of example:
  * `chmod g=x filename`



