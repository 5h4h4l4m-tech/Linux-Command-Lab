
#Tag: #Basic #Network #System #KaliLinux


#BASIC COMMANDS
1. ls          #List files and folders
2. ls -la      #List all files with details including hidden
3. pwd         #Print Working Directory - show current location
4. cd /path    #Change Directory - go to folder
5. cd..        #Go back one folder
6. mkdir name  #MaKe DIRectory - create new folder
7. rmdir name  #Remove empty directory
8. rm file     #ReMove file
9. rm -rf dir  #ReMove Force - delete folder without asking
10. cp a b     #CoPy file from a to b
11. mv a b     #MoVe or Rename file
12. touch file #Create empty file
13. cat file   #ConCATenate - show file content
14. less file  #Read large file page by page
15. nano file  #Open file in Nano text editor
16. vim file   #Open file in Vim text editor
17. clear      #Clear terminal screen
18. history    #Show command history

#SYSTEM & INFO
19. uname -a   #Unix NAME - show OS and kernel info
20. df -h      #Disk Free - show disk space
21. du -sh dir #Disk Usage - show folder size
22. free -h    #Show RAM usage
23. top        #Show running processes live
24. ps aux     #Process Status - show all processes
25. kill 1234  #Kill process by PID
26. killall app#Kill process by name
27. uptime     #Show how long system is running
28. date       #Show current date and time
29. reboot     #Restart system
30. shutdown now #Shutdown system immediately

#USER & PERMISSION
31. whoami     #Show current user name
32. id         #Show user ID and groups
33. sudo su    #Switch to SuperUser - root access
34. sudo cmd   #Run command as root
35. passwd     #Change PASSWorD
36. useradd u  #ADD new USER
37. userdel u  #DELete USER
38. usermod -aG sudo u #Add user to sudo group
39. chmod 755 f#CHange MODe - set permissions
40. chmod +x f #Add eXecute permission
41. chown u:u f#CHange OWNer of file
42. chgrp g f  #CHange GRouP of file

#NETWORK
43. ip a       #Show IP Addresses
44. ifconfig   #Show network interfaces
45. ping site  #Check if site is online
46. traceroute #Trace route to destination
47. netstat -tulpn #Show open ports and services
48. ss -tulpn  #Socket Statistics - show connections
49. wget url   #DownLoad file from URL
50. curl url   #Transfer data from URL
51. ssh u@ip   #Secure SHell - remote login
52. scp f u@ip #Secure CoPy file to remote

#PACKAGE MANAGEMENT
53. apt update     #Update package list
54. apt upgrade -y #Upgrade all packages
55. apt install pkg#Install package
56. apt remove pkg #Remove package
57. apt purge pkg  #Remove package with config
58. apt search pkg #Search package
59. apt list --installed #List installed packages

#FILE SEARCH & TEXT
60. grep "word" f  #Global REgular Print - find text
61. grep -r "w" /  #Recursive grep in folder
62. find / -name "*.txt" #Find files by name
63. wc file        #Word Count - lines words chars
64. sort file      #SORT lines alphabetically
65. uniq file      #Remove duplicate lines
66. head -n 10 f   #Show first 10 lines
67. tail -n 10 f   #Show last 10 lines
68. tail -f log    #Follow log file live
69. awk '{print $1}' #Print first column
70. sed 's/a/b/g'  #Stream EDitor - replace text

#COMPRESSION
71. tar -cvf a.tar dir #Create TAR archive
72. tar -xvf a.tar     #Extract TAR archive
73. tar -czvf a.tgz dir#Create gzipped TAR
74. tar -xzvf a.tgz    #Extract gzipped TAR
75. gzip file      #GZIP compress file
76. gunzip file.gz #GZIP decompress
77. zip a.zip dir  #ZIP folder
78. unzip a.zip    #UNZIP file

#GIT & SCRIPTS
79. git clone url  #CLONE git repository
80. git status     #Show git status
81. git pull       #PULL latest changes
82../script.sh    #Run script
83. bash script.sh #Run with bash
84. chmod +x s.sh  #Make script eXecutable

#SERVICES
85. systemctl start svc  #START service
86. systemctl stop svc   #STOP service
87. systemctl status svc #Check STATUS
88. systemctl enable svc #Enable on boot
89. crontab -e     #Edit CRON TAB tasks

#KALI TOOLS
90. nmap -sV target #Network MAPper - scan ports
91. msfconsole      #Metasploit Framework console
92. airmon-ng       #AIR MONitor - wifi cards
93. airodump-ng wlan0 #Capture wifi packets
94. hydra           #Brute force login tool
95. john            #JOHN the ripper - password cracker
96. wireshark       #Packet analyzer GUI

#NOTE: Use only on your own lab or systems you have permission to test.
