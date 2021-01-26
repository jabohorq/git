# BASH SCRIPT

## PARAMETERS
`$0` name of the script (path included)<br\>
`$1` First parameter
*Example:* <br/>
`touch parameters.sh`<br/>
`chmod 755 parameters.sh` (All permision for user, read and execute permission for the rest )<br/>
*Script* parameters.sh<br/>
`#!/bin/bash/`<br/>
`# First parameter is assigned to variable USER_NAME`<br/>
`USER_NAME=$1`<br/>
`echo Hello $USER_NAME`<br/>
`echo $(date)`<br/>
`echo $(pwd)`<br/>
`# If the program execute sucessfully returns 0`<br/>
`exit 0`<br/>
*Usage:* ./parameters.sh Peter <br/>
*output:* Hello Peter--date--current path

## IF-ELSE statement
`if [ cond1 ]`<br/>
`then`<br/>
`echo 'message1'`<br/>
`elif[ cond2 ]`<br/>
`then `<br/>
`echo 'message2'`<br/>
`else`<br/>
`echo 'message2'`<br/>
`fi`

## WHILE
