# Born2beroot
Virtual machine 
### Basic commands
1. SSH status
`systemctl status ssh`
`sudo vim /etc/ssh/sshd_config`
3. To ssh to my virtual box
Firstly I configured the network settings to bridged adapter
Secondly i typed `hostname -I` command in my virtual box to get the hostname ip
After that just type `ssh quanguye@<hostname -I> -p 4242` in my terminal
4. Password managing
`sudo vi /etc/pam.d/common-password` to view the configuration file
5. Managing users
To add a user user `adduser <name>`
`getent group` to see all available groups
`getent <groupname>` to see users in thata group
6. View sudoers file
`sudo visudo`
7. Viewing monitoring.sh script`
vim /usr/local/bin/monitoring.sh`
8. `sudo var/log/sudo` theres the sudo.log file
9. sudo adduser <new username>
10. `sudo ufw status numbered`
11. add user`sudo usermod -a -G examplegroup exampleusername`
