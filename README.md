# Born2beroot
Virtual machine 
### Basic commands
1. SSH status
`systemctl status ssh`
2. To ssh to my virtual box
Firstly I configured the network settings to bridged adapter
Secondly i typed `hostname -I` command in my virtual box to get the hostname ip
After that just type `ssh quanguye@<hostname -I> -p 4242` in my terminal
3. Password managing
`sudo vi /etc/pam.d/common-password` to view the configuration file
4. Managing users
To add a user user `adduser <name>`
`getent group` to see all available groups
`getent <groupname>` to see users in thata group
5. View sudoers file
`sudo vim /etc/sudoers.d`
6. Viewing monitoring.sh script
vim /usr/local/bin/monitoring.sh
