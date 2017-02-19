

# /BIN folder explained

 - **/BIN** FOLDER
/bin: Stands for binary. This folder contains base executables which are required for minimal system working. These commands are available in runlevel 1 for basic administration. Commands which are available in /bin folder is accessed by every one and can run by every user. This folder contains basic commands such as cat, chmod, chgrp, chown, date, dir, dd, df, ln, mv, echo and zipping tools such as bzip, gzip etc.

- **/SBIN FOLDER**
/sbin: This folder stands for system binaries or super user binaries. This folder contains commands which are required for changing system properties or system level settings such as disk management, network management etc. This folder is accessed some times by normal user but they can not execute any of the commands located in this and what ever commands/scripts located in this folder are run only by root user. If you want to make normal user to run these commands you have to implement SUDO or Powerbroker to give elevated access. Some of the commands available in this folder are chkconfig, dhcpclient, fsck and it’s related commands, ifconfig and it’s related commands, init and it’s related commands, lvm and it’s related commands etc.

- **/USR/BIN** FOLDER
/usr/bin: This folder is similar to /bin. This folder contains normal commands which are an extend set of commands to /bin folder for normal user and not that much essential to run the machine. This folder contains commands such as at, atq, bc, awk, cal, cmp, dig, diff, du, env, find, free, ftp, gcc, groups, id, info iostat, last, lsof, md5sum, nmap, rar, seq, tail, top, vi, unzip, who.

- **/USR/SBIN** FOLDER
/usr/sbin: This folder is similar to /sbin. This folder contain system commands which are an extend set of commands to /sbin folder for root user and not that much essential to run the machine. This folder contain commands such as arp, adduser, cron, cups related commands, grub related commands, kvm, ppp related commands, tcpdump etc.

- **/PATH/TO/SOME/BIN**
Some times you will see bin folder in other locations such as /usr/local/bin this is the place you can see some of the binaries which are installed on the system locally. Some time you can see a bin folder in /opt which indicates that some binaries are located in this /opt bin folder.

- **/PATH/TO/SOME/SBIN**
Some times you will see bin folder in other locations such as /usr/local/sbin this is the place you can see some of the binaries which are installed on the system locally and are system related commands. Some time you can see a sbin folder in /opt which indicates that some binaries are located in this /opt/bin folder.

# Resources

- [LINUX DIRECTORY STRUCTURE EXPLAINED: /BIN FOLDER] (http://www.linuxnix.com/linux-directory-structure-explained-bin-folder/)
