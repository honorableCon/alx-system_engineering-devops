# Shell Permissions Chapter

## Tasks

0. My name is Betty

> Create a script that switches the current user to the user betty.
> command : `su betty`

1. Who am I

> Write a script that prints the effective username of the current user.
> command : `whoami`

2. Groups

> Write a script that prints all the groups the current user is part of.
> command : `groups`

3. New owner

> Write a script that changes the owner of the file hello to the user betty.
> command : `chown betty hello`

4. Empty!

> Write a script that creates an empty file called hello.
> command : `touch hello

5. Execute

> Write a script that adds execute permission to the owner of the file hello.
> command : `chmod u+x hello`

6. Multiple permissions

> Write a script that adds execute permission to the owner and the group owner, and read permission to other users, to the file hello.
> command : `chmod ug+x,o+r hello`

7. Everybody

> Write a script that adds execution permission to the owner, the group owner and the other users, to the file hello
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
> -rwxr-x-wx 1 julien julien 23 Sep 20 14:25 hello
> command : `chmod 753 hello`

10. Look in the mirror

> Write a script that sets the mode of the file hello the same as olleh’s mode.
> command : `chmod --reference=olleh hello`
