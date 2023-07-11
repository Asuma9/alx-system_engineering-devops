alias name='value' - create an alias
echo 'hello $USER' - display the current user with a salutation
export PATH=$PATH:/action - add /action to the PATH with action being last directory the shell seraches for a program.
echo $((' echo $PATH | grep -o ":/" | wc -l ' +1)) - count the number of directories in the PATH
printenv - command to print environment variables
set - command to print all variables including global
varname='value' - command that creates a local variable
varname='value' - command that creates a global variable
echo $((value+$filename)) - command to print the sum of a value passed to a value stored in the environment variable'
echo $(($POWER/$RULE)) - command to recall environment variables ofr arithmetic execution
echo $((BREATH**LOVE)) - display an exponent
echo $((2#$BINARY)) - Convert number stored in BINARY variable to decimal from base 2
echo {a..z}{a..} | tr " " "\n" | grep -v "oo" - Print alphabetical number combinations except for 'oo'
