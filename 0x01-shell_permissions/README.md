Task 0: Create a script that switches the current user to the user betty.
You should use exactly 8 characters for your command (+1 character for the new line) - su betty

Task 1: Write a script that prints the effective username of the current user - id -u -n

Task 2: Write a script that prints all the groups the current user is part of - groups

Task 3: Write a script that changes the owner of the file hello to the user betty - sudo chown betty hello

Task 4: Write a script that creates an empty file called hello - touch hello

Task 5: Write a script that adds execute permission to the owner of the file hello.
The file hello will be in the working directory - chmod u+x hello

Task 6: Write a script that adds execute permission to the owner and the group owner, and read permission to other users, to the file hello.
The file hello will be in the working directory - chmod u+x,g+x,o+r hello
