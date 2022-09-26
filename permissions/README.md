# Shell Permissions [*"Linux"*](https://www.linux.com/what-is-linux/)

***As the word "Permission" self-implies within (the action of officially allowing someone to do a particular thing). So is our scenario. To effect several codes, you should have permission or, in other words, allowance from the security system to execute the effect. To make it happen Unix has developed significant codes.*** ↓

* *["chmod"](http://linuxcommand.org/lc3_man_pages/chmod1.html)* - **Modify file access rights.**
* *["su"](http://linuxcommand.org/lc3_man_pages/su1.html)* - **Temporarily become the superuser.**
* *["sudo"](http://linuxcommand.org/lc3_man_pages/sudo8.html)* - **Temporarily become the superuser.**
* *["chown"](http://linuxcommand.org/lc3_man_pages/chown1.html)* - **Change file ownership.**
* *["chgrp"](http://linuxcommand.org/lc3_man_pages/chgrp1.html)* - **Change a file's group ownership.**


***You can view the status of Permissions mainstream by using the command `ls -l`.The display should look something like this:*** ↓

```Shell
-rwxr--r-- 1 root  X
-rwxr--r-- 1 root  Y
-rwxr--r-- 1 root  Z   
```

---

* [My name is Betty](https://github.com/PatrikZh/holbertonschool-shell/blob/main/permissions/0-iam_betty) ↓

`Create a script that switches the current user to the user betty
`

---
* [***Who am I***](https://github.com/PatrikZh/holbertonschool-shell/blob/main/permissions/1-who_am_i) ↓

`Write a script that prints the effective username of the current user
`

---
* [***Groups***](https://github.com/PatrikZh/holbertonschool-shell/blob/main/permissions/2-groups) ↓

`Write a script that prints all the groups the current user is part of.
`

---
* [***New Owner***](https://github.com/PatrikZh/holbertonschool-shell/blob/main/permissions/3-new_owner) ↓

`Write a script that changes the owner of the file hello to the user betty.
`

---
* [***4-listmorefiles***](https://github.com/PatrikZh/holbertonschool-shell/blob/main/permissions/4-empty) ↓

`Write a script that creates an empty file called hello.
`

---
* [***Empty!***](https://github.com/PatrikZh/holbertonschool-shell/blob/main/permissions/4-empty) ↓

`Write a script that adds execute permission to the owner of the file hello.
`

---
* [***Execute***](https://github.com/PatrikZh/holbertonschool-shell/blob/main/permissions/5-execute) ↓

`Write a script that adds execute permission to the owner and the group owner, and read permission to other users, to the file hello.
`

---
* [***Multiple permissions***](https://github.com/PatrikZh/holbertonschool-shell/blob/main/permissions/6-multiple_permissions) ↓

`Write a script that adds execution permission to the owner, the group owner and the other users, to the file hello
`

---
* [***Everybody!***](https://github.com/PatrikZh/holbertonschool-shell/blob/main/permissions/7-everybody) ↓

`Write a script that sets the permission to the file hello as follows:
Owner: no permission at all
Group: no permission at all
Other users: all the permissions`

---
* [***James Bond***](https://github.com/PatrikZh/holbertonschool-shell/blob/main/permissions/8-James_Bond) ↓

`To change permission as requested `

---
* [***John Doe***](https://github.com/PatrikZh/holbertonschool-shell/blob/main/permissions/9-John_Doe) ↓

`Changes the permission to file hello number (753)`

---
* [***Look in the mirror***](https://github.com/PatrikZh/holbertonschool-shell/blob/main/permissions/10-mirror_permissions) ↓

`Changes permission to file hello`

---
* [***Directories***](https://github.com/PatrikZh/holbertonschool-shell/blob/main/permissions/11-directories_permissions) ↓

`Create a script that adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users. Regular files should not be changed.
`

---
* [***More Directories***](https://github.com/PatrikZh/holbertonschool-shell/blob/main/permissions/12-directory_permissions) ↓

`Create a script that creates a directory called my_dir with permissions 751 in the working directory.
`

---
* [***Change Group***](https://github.com/PatrikZh/holbertonschool-shell/blob/main/permissions/13-change_group) ↓

`Write a script that changes the group owner to school for the file hello
`

---
* [***Owner and group***](https://github.com/PatrikZh/holbertonschool-shell/blob/main/permissions/14-change_owner_and_group) ↓

`Write a script that changes the owner to vincent and the group owner to staff for all the files and directories in the working directory.`

---
* [***Symbolic links***](https://github.com/PatrikZh/holbertonschool-shell/blob/main/permissions/15-symbolic_link_permissions) ↓

`Write a script that changes the owner and the group owner of _hello to vincent and staff respectively.`

---
* [***If Only***](https://github.com/PatrikZh/holbertonschool-shell/blob/main/permissions/16-if_only) ↓

`Write a script that changes the owner of the file hello to vincent only if it is owned by the user guillaume.`

---

                                      So long! #Holbie
   ![Image](https://images.squarespace-cdn.com/content/v1/5a4bfe8bf09ca4228ceca3b7/1539139199598-ANH454IHZI1OKWONKRXY/logo.jpg?format=2500w)
