echo 'Hello, World' - Print Hello, World
echo '"(Ôo)' -  Print a confused smiley
cat /etc/passwd - display the contents of the file /etc/passwd
Cat file1 file - Display contents of 2 files
tail -n filename - Display the last n lines of filename 
head -n filename - Display the first n lines of filename
head -n filename | tail +n
\*\\'"Best School"\'\\*$\?\*\*\*\*\*:)- Creating silent files 
ls -la > filename - save current state of directory
tail -qn 1 iacta- duplicate last line of iacta file
find . -type f -name '*.js' -delete - remove file with specified parten
find . -type d -not -name '.' | wc -l - delete all directories and sub-directories in the current directory
ls -t | head 10 - print newest 10 files  in the current directory
uniq -u filename - prints only unique elements of filename
grep -l 'root' filename - displays lines that match specified partten
grep -i 'bin' -A n - display number of lines that contain the pattern bin
grep -A 3 'pattern'  filename - print lines after matching pattern
rep !'pattern' filename- display files that dont match the pattern
grep -i 'n*' - display all lines of filename starting with a letter.
tr 'A' 'Z' | 'c' 'e' - repalceA for Z and c for e from input respectively.
tr -d 'cC' or sed 's/[cC]//g' - remove specified letters
rev - script to reverse output
cut -d ':' -f 1,6 /etc/passwd | sort - prints sorted list of all users
find . -empty | rev | cut -d '/' -f 1 | rev - find all empty files and directories in the current directory and subdirectories.
find -type f -name '*.gif' |rev|cut -d '/' -f 1 | cut -d '.' -f 2- |rev|LC_ALL=C sort -f - list all files with '.gif' extension in the current directory and all its sub-directories
echo $(cut -c 1 | tr -d '\n') - Script to decode acrostics that use the first letter of each line 
tail -n +2 | cut -f -1 | sort -k 1 | uniq -c | sort -rnk 1 | head -n 11 | rev | cut -d '' -f -1 | rev - script that parses web servers logs in TSV format as input and displays the 11 hosts or IP addresses which did the most requests
