Task 0: Create a script that creates an alias.
Name: ls
Value: rm * - alias ls="rm *"

Task 1: Create a script that prints hello user, where user is the current Linux user. - echo "hello $USER"

Task 2: Add /action to the PATH. /action should be the last directory the shell looks into when looking for a program - PATH=$PATH:/action

Task 3: Create a script that counts the number of directories in the PATH - echo $PATH | tr ":" "\n" | wc -l

Task 4: Create a script that lists environment variables - printenv

Task 5: Create a script that lists all local variables and environment variables, and functions - set

Task 6: Create a script that creates a new local variable.
Name: BEST
Value: School - BEST="School"

Task 7: Create a script that creates a new global variable.
Name: BEST
Value: School - export BEST="School"

Task 8: Write a script that prints the result of the addition of 128 with the value stored in the environment variable TRUEKNOWLEDGE, followed by a new line -echo ((128+TRUEKNOWLEDGE))

Task 9: Write a script that prints the result of POWER divided by DIVIDE, followed by a new line.
POWER and DIVIDE are environment variables - echo $((POWER/DIVIDE))

Task 10: rite a script that displays the result of BREATH to the power LOVE
BREATH and LOVE are environment variables
The script should display the result, followed by a new line - echo ((BREATH**LOVE))
