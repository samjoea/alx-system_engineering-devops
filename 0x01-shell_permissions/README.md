### These are all the scripts in the 0x01-shell_permissions folder and what they do

---

- **0-iam_betty :** changes the current user to betty

- **1-who_am_i :** Prints the effective username of the current user.

- **2-groups :** Prints all groups that current user is part of.

- **3-new_owner :** Changes the owner of the file hello to betty.

- **4-empty :** Creates and empty file called hello.

- **5-execute :** Adds execute permission to the owner of the file hello.

- **6-multiple_permissions :** Adds executing permission to owner and group, and reading permission to other users for the file hello.

- **7-everybody :** Sets executing permission for all users of the file hello.

- **8-James_Bond :** Sets the permission of the file hello as no permission for owner and group and all for other users.

- **9-John_Doe :** Sets the mode of the file hello to `-rwxr-x-wx`.

- **10-mirror_permissions :** Sets the mode of file hello to the same as the mode of file olleh.

- **11-directories_permissions :** Adds execute permission to all subdirectories of the current directory for all users.

- **12-directory_permissions :** Creates a directory my_dir with chmod 751 in working directory.

- **13-change_group :** Changes the group ower of file hello to school.

- **100-change_owner_and_group :** Changes the owner to vincent and group owner to staff fot all the files and directories in the working directory.

- **101-symbolic_link_permissions :** Changes the owner and group owner of symbolic link _hello to vincent and staff.

- **102-if_only :** Changes the owner of the file hello to betty if the file is owned by the user guillaume.

- **103-Star_Wars :** Play the StarWars IV episode in the terminal.
