# Notes on Shell Scripting

## - It is used to write comments information about the script

# It is used for debugging of script writen at starting
set -x 

# It is used to check number of process of applications or systems running/dead/zombies 
ps -ef (ps - process, f - full format)

# It is used for filtering the information from output
grep

# It is used for forwarding the output from first command to next command
| (pipe)

# It is used for filtering out various columns from rows. Below one filters first columns from a row.
Eg: awk -F" " {print $1}






