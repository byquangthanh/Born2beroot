# Born2beroot
Virtual machine 
### Basic commands
1. SSH status
`systemctl status ssh`
2. To ssh to my virtual box
Firstly I configured the network settings to bridged adapter
Secondly i typed `hostname -I` command in my virtual box to get the hostname ip
After that just type `ssh quanguye@<hostname -I> -p 4242` in my terminal
