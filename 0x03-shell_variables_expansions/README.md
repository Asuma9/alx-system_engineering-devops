alias name='value' - create an alias
echo 'hello $USER' - display the current user with a salutation
export PATH=$PATH:/action - add /action to the PATH with action being last directory the shell seraches for a program.
echo $((' echo $PATH | grep -o ":/" | wc -l ' +1)) - count the number of directories in the PATH
printenv - command to print environment variables
set - command to print all variables including global
varname='value' - command that creates a local variable
