---
Name: Rahad Kabir
semester: spring 22
---
# Wildcards
* The main wildcard is a star, or asterisk (*) character.
* A star alone matches anything and nothing and matches any number of chracters.

# Brace expansion and how to use it
* Brace expansion {} is not a wildcard but another feature of bash that allows you to generate arbitrary strings to use use with commands.
## Examples,
### To create a whole directory structure in a single command:
* mkdir -p music/{jazz,rock}/{mp3files,videos,oggfiles}/new{1..3}
### To create a N number of files use:
* touch website{1..5}.html
### Remove multiple files in a single directory:
* rm -r {dir1,dir2,dir3,file.txt,file.py}