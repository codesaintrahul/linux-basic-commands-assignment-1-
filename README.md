# linux-basic-commands-assignment-1-
Linux basic commands assignment

#1..

-->code_saint@Rahul-IdeaPad-Gaming-3-15IAH7:-/rahul/devops/assignment$ mkdir test_dir

-->code_saint@Rahul-IdeaPad-Gaming-3-15IAH7:-/rahul/devops/assignments touch example.txt

-->code_saint@Rahul-IdeaPad-Gaming-3-151AH7:-/rahul/devops/assignment$ cd test_dir

-->code_saint@Rahul-IdeaPad-Gaming-3-15IAH7:-/rahul/devops/assignment/test_dir$ touch example.txt

-->code_saint@Rahul-IdeaPad-Gaming-3-15IAH7:-/rahul/devops/assignment/test_dir$ mv example.txt renamed_example.txt


#2

-->code_saint@Rahul-IdeaPad-Gaming-3-15IAH7:~/rahul/devops/assignment/test_dir$ cat /etc/passwd

-->code_saint@Rahul-IdeaPad-Gaming-3-151AH7:-/rahul/devops/assignment/test dir$ head /etc/passwd

root:x:0:0:root:/root:/bin/bash
daemon:x:1:1:daemon:/usr/sbin:/usr/sbin/nologin
bin:x:2:2:bin:/bin:/usr/sbin/nologin
sys:x:3:3:sys:/dev:/usr/sbin/nologin
sync:x:4:65534:sync:/bin:/bin/sync
games:x:5:60:games:/usr/games:/usr/sbin/nologin
man:x:6:12:man:/var/cache/man:/usr/sbin/nologin
lp:x:7:7:1p:/var/spool/lpd:/usr/sbin/nologin
mail:x:8:8:mail:/var/mail:/usr/sbin/nologin
news:x:9:9:news:/var/spool/news:/usr/sbin/nologin

-->code_saint@Rahul-IdeaPad-Gaming-3-15IAH7:-/rahul/devops/assignment/test_dirs tail /etc/passwd

hplip:x:116:7:HPLIP system user,,,:/run/hplip:/bin/false
gnome-remote-desktop:x:988:988: GNOME Remote Desktop:/var/lib/gnome-remote-desktop:/usr/sbin/nologin
polkitd:x:987:987:User for polkitd:/:/usr/sbin/nologin
rtkit:x:117:119:RealtimeKit,.,:/proc:/usr/sbin/nologin
colord:x:118: 120:colord colour management daemon...:/var/lib/colord:/usr/sbin/nologin
gnome-initial-setup:x: 119:65534::/run/gnome-initial-setup/:/bin/false
gdm:x:120:121:Gnome Display Manager:/var/lib/gdm3:/bin/false
nm-openvpn:x:121:122: Network Manager OpenVPN,,,:/var/lib/openvpn/chroot:/usr/sbin/nologin nvidia-persistenced:x: 122:124:NVIDIA Persistence Daemon...:/nonexistent:/usr/sbin/nologin
code_saint:x:1000:1000: Rahul:/home/code_saint:/bin/bash

#3

-->code_saint@Rahul-IdeaPad-Gaming-3-15IAH7:-/rahul/devops/assignment/test_dir$ cat /etc/passwd |

grep root
root:x:0:0:root:/root:/bin/bash
nm-openvpn:x:121:122:NetworkManager OpenVPN,,,:/var/lib/openvpn/chroot:/usr/sbin/nologin

#4


-->code_saint@Rahul-IdeaPad-Gaming-3-151AH7:-/rahul/devops/assignments zip -r test dir.zip test_dir

adding: test_dir/ (stored 0%)
adding: test dir/renamed_example.txt (stored 0%)


-->code_saint@Rahul-IdeaPad-Gaming-3-15IAH7:-/rahul/devops/assignments unzip test_dir.zip unzipped_dir

Archive: test dir.zip
caution: filename not matched: unzipped_dir


#5

-->code_saint@Rahul-IdeaPad-Gaming-3-15IAH7:-/rahul/devops/assignment$ wget https://example.com/sample.txt

--2026-01-16 20:02:16 https://example.com/sample.txt
Resolving example.com (example.com)... 2606:4700:8d92:8c7c:33d9:bd:ccc4:a209, 104.18.27.120, 104.18.26.120
Connecting to example.com (example.com) | 2606:4700:8d92:8c7c:33d9:bd:ccc4:a209|:443... connected.
HTTP request sent, awaiting response... 404 Not Found
2026-01-16 20:02:16 ERROR 404: Not Found.

#6


-->code_saint@Rahul-IdeaPad-Gaming-3-15IAH7:-/rahul/devops/assignments touch secure.txt

-->code_saint@Rahul-IdeaPad-Gaming-3-15IAH7:-/rahul/devops/assignments ls

secure.txt test dir test_dir.zip

-->code_saint@Rahul-IdeaPad-Gaming-3-151AH7:-/rahul/devops/assignment$ chmod 444 secure.txt code_saint@Rahul-IdeaPad-Gaming-3-1SIAH7:-/rahul/devops/assionnents ls -l secure.txt

٠٢٠٠٢٠٠٢٠٠ 1 code saint code saint @ Jan 16 20:03 secure.txt

#7

-->code_saint@Rahul-IdeaPad-Gaming-3-15IAH7:-/rahul/devops/assignment$ export MY_VAR="Hello, Linux!"

-->code_saint@Rahul-IdeaPad-Gaming-3-15IAH7:-/rahul/devops/assignments echo SMY_VAR

Hello, Linux!

-->code_saint@Rahul-IdeaPad-Gaming-3-151AH7:-/rahul/devops/assignment$ ls

secure.txt test dir test_dir.zip







