# 0-iam_betty

0-iam_betty: script that switches the current user to the user `betty`

# 1-who_am_i

1-who_am_i: script that prints the effective username of the current user

# 2-groups

2-groups: script that prints all the groups the current user is part of

# 3-new_owner

3-new_owner: script that changes the owner of the file `hello` to the user `betty`

# 4-empty 

4-empty: script that creates an empty file called `hello`

# 5-execute

5-execute: script that adds execute permission to the owner of the file `hello`

# 6-multiple_permissions

6-multiple_permissions: script that adds excute permission to the owner and the group owner, and read permission to other users, to the file `hello`

# 7-everybody

7-everybody: script that adds execution permission to the owner, the group owner and the other users, to the file `hello`

# 8-James_Bond

8-James_Bond: script that sets the permission to the file hello as follows:
. Owner: no permission at all
. Group: no permission at all
. Other users: all the permissions

# 9-John_Doe

9-John_Doe: script that sets the mode of the line `hello` to this:
`-rwxr-x-wx 1 julien julien 23 Sep 20 14:25 hello`

# 10-mirror_permissions

10-mirror_permissions: script that sets the mode of the file `hello` the same as `olleh`'s mode:
`-rw-rw-r-- 1 julien julien  0 Sep 20 14:43 olleh`

# 11-directories_permissions

11-directories_permissions: script that adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users. (Regular files should not be changed.)

# 12-directory_permissions

12-directory_permissions: script that creates a directory called `my_dir` with permissions 751 in the working directory

# 13-change_group

13-change_group: script that changes the group owner to `school` for the file `hello`

# 14-change_owner_and_group

14-change_owner_and_group: script that changes the owner to `vincent` and the group owner to `staff` for all the files and directories in the working directory.

# 15-symbolic_link_permissions

15-symbolic_link_permissions: script that changes the owner and the group owner of `_hello` to `vincent` and `staff` respectively.
The file _hello is in the working directory
The file _hello is a symbolic link

# 16-if_only

16-if_only: script that changes the owner of the file `hello` to `vincent` only if it is owned by the user `guillaume`.

The file hello will be in the working directory
