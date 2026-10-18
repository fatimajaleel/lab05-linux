# Question 1: Current user and home folder
Answer: I am logged in as fatimajaleel. My home folder is /home/fatimajaleel.
Commands: whoami, pwd

# Question 2: Server name and Ubuntu version
Answer: My server name is ubuntu. I am using Ubuntu 24.04.3 LTS.
Commands: hostname, cat /etc/os-release | head -2

# Question 3: RAM and free disk space
Answer: My server has approximately 1.6 GiB of RAM. My root filesystem has 2.6 GB available disk space.
Commands: free -h, df -h /

# Question 4: Users that can log in with /bin/bash
Answer: The users shown with /bin/bash shell are root and fatimajaleel.
Command: grep "/bin/bash" /etc/passwd

# Question 5: Processes running right now
Answer: Approximately 244 processes are running right now.
Command: ps aux | wc -l

# Question 6: Creation and deletion time of lab5user
Answer: lab5user was created and deleted during Lab 05 execution.
Command: sudo grep lab5user /var/log/auth.log
