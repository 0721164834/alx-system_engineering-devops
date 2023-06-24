#!/bin/bash
for the following scripts:
0-iam_betty it switches the current user to the user betty.
1-who_am_i this script prints the effective user namme of the current user.
2-groups this sript prints all the groups in the current user part of.
3-new_owner this script changes the owner file hello to the user betty.
4-empty this script  creates an empty file called 4-empty.
5-execute this script adds execute permission to the owner of the file hello.
6-mulitiple_permisions this script adds execute permission  to the owner and the group owner, and read permission to other users, to the hello file.
7-everybody this script adds an execution permission to the owner, the group owner and other users to the file hello.
8-James_Bond this script sets the permission to the file hello as follows:
-Owner: no permission at all
-Group: no permission at all
-Other users: all the permissions
9-John_Doe this script sets the mode of hello file this:
-rwxr-x-wx 1 julien julien 23 Sep 20 14:25 hello
10-mirror_permissions this script sets the mode of file hello the same as olleh's mode.
11-directories_permissions this script adds  execute permission to all subdirectories of current directory for the owner, the group owner and all oter user.
12-directory_permissions this script creates a directory called my_dir with permision 751 in the working directory.
13-change_group this script changes the group owner to school for the file hello.
101-symbolic_link_permisions this script changes the owner and the group ower of the _hello to Vincent and staff respectively.
102-if_only this script  changes the owner of the file hello to betty only if it is owned by the user guillaume.
103-Star_Wars this script will play the StarWars IV episode in the terminal.

#Do hard things
#keep pushing
