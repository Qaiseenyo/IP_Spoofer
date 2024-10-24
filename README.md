# IP_Spoofer
A simple python script to spoof IP Address by sending ICMP packets from fake IPs

Commands needed to run this script:

1) sudo pip3 -r install requirements.txt
(install it in sudo otherwise the faker module wont be recognized by python
because it will be installed in the normal user environment not the root,
you need sudo to run this script, check if its installed by running: sudo pip3 list)
2) sudo IP_Spoofing.py [target_IP]
