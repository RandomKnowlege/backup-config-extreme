This project contains a collection of scripts to set automatic backups for the config files. 
Before using, make sure to change the value of $tftpip to match the IP address of your tftp server in both scripts.
Place both scripts in a directory in your tftp server and transfer UPSSetup.xsf to the switch to run the setup. 
Each time the resulting UPM profile runs it will download the backup script so it has a known good copy.