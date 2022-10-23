This directory contains the following scripts:
1. 0-iam_betty, switches the current user to user betty.
2. 1-who_am_i, prints the effective username of the current user.
3. 2-groups, prints all the groups the current user is a part of.
4. 3-new_owner, changes the owner of the file hello to the user betty.
5. 4-empty, creates an empty file hello.
6. 5-execute, adds execute permission to the owner of the file hello.
7. 6-multiple_permissions, adds execute permission to the owner and the group owner, and read permission to other users, to the file hello.
8. 7-everybody, adds execution permission to the owner, the group and the other users, to the file hello.
9. 8-James_Bond, gives the user and group no permission at all and others all the permissions.
10. 9-John_Doe, sets the permission of the file hello to -rwxr-x-wx.
11. 10-mirror_permissions, sets the mode of the file hello to the same as olleh's.
12. 11-directories_permissions, adds execute permission to add subdirectories of the current directory for the owner, the group owner and all other users. Regular files should not be changed.
13. 12-directory_permissions, creates a directory called my_dir with permissions 751 in the working directory.
14. 13-change_group, changes the goup owner to school for the file hello, the file hello will be in the working directory.
15. 100-change_owner_and_group, changes the owner to vincent and the group owner to staff for all the files and directories in the working directory.
16. 101-symbolic_link_permissions, changes the owner and the group owner of _hello to vincent and staff respectively, where _hello is a symbolic link.
17. 102-if_only, changes the owner of the file hello to betty only if it is owned by the user guillaume.
18. 103-Star_Wars, plays the StarWars IV episode in the terminal.
