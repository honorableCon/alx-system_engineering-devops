# Shell Permissions Chapter

## Tasks

0. My name is Betty

> Create a script that switches the current user to the user betty.<br>
> command : `su betty`

1. Who am I

> Write a script that prints the effective username of the current user.<br>
> command : `whoami`

2. Groups

> Write a script that prints all the groups the current user is part of.<br>
> command : `groups`

3. New owner

> Write a script that changes the owner of the file hello to the user betty.<br>
> command : `chown betty hello`

4. Empty!

> Write a script that creates an empty file called hello.<br>
> command : `touch hello

5. Execute

> Write a script that adds execute permission to the owner of the file hello.<br>
> command : `chmod u+x hello`

6. Multiple permissions

> Write a script that adds execute permission to the owner and the group owner, and read permission to other users, to the file hello.<br>
> command : `chmod ug+x,o+r hello`

7. Everybody

> Write a script that adds execution permission to the owner, the group owner and the other users, to the file hello. <br>
> command : `chmod +x hello`

8. James Bond

> Write a script that sets the permission to the file hello as follows:

    - Owner: no permission at all
    - Group: no permission at all
    - Other users: all the permissions

The file hello will be in the working directory You are not allowed to use commas for this script

> command : `chmod 007 hello`

9. John Doe

> Write a script that sets the mode of the file hello to this:

    -rwxr-x-wx 1 julien julien 23 Sep 20 14:25 hello

> command : `chmod 753 hello`

10. Look in the mirror

> Write a script that sets the mode of the file hello the same as olleh’s mode.<br>
> command : `chmod --reference=olleh hello`

11. Directories

> Create a script that adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users. Regular files should not be changed.<br>
> command : `chmod -R +X .`

12. More directories

> Create a script that creates a directory called my_dir with permissions 751 in the working directory.<br>
> command : `mkdir -m 751 my_dir`

13. Change group


> Write a script that changes the group owner to school for the file hello<br>
> command : `chgrp school hello`

14. Owner and group

> Write a script that changes the owner to vincent and the group owner to staff for all the files and directories in the working directory.<br>
> command : `chown -R vincent:staff *`

15. Symbolic links

> Write a script that changes the owner and the group owner of _hello to vincent and staff respectively.

    The file _hello is in the working directory
    The file _hello is a symbolic link

> command : `chown -h vincent:staff _hello`

16. If only 

> Write a script that changes the owner of the file hello to betty only if it is owned by the user guillaume.<br>
> command : `chown --from=guillaume betty hello`

17. Star Wars

> Write a script that will play the StarWars IV episode in the terminal.<br>
> command : `telnet towel.blinkenlights.nl`
