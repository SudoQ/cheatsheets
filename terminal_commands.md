#1 Terminal commands
A collection of commands which is good to know

#2 Tar
|Cmd|Description|
|----|----|
|tar -xf archive.tar.gz|Extract files|
|curl example.com/tarball.tar.gz &#124; tar -xf -|Downloads the selected tarball and unpacks it

#3 Networking
|Cmd|Description|
|----|----|
|ip addr &#124 grep 'state UP' -A2 &#124 tail -n1 &#124 awk '{print $2}' &#124 cut -f1  -d'/'|Get you ip addr|
|nmap -sL <ipaddr>/24|Scan the local network, useful for finding your ssh-server|
|screen -d -m cmd|Run a command in a screen session and detatch|
|screen -r|Restore a detatched screen session|
