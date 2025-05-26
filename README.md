Nmap Network Scanning and Analysis

In this task, I used Nmap to perform a network scan on my local network to identify active hosts and detect open ports. The objective was to gain hands-on experience in basic network reconnaissance techniques and understand how to analyze scan results for potential security risks.

First, I installed Nmap on my system. Then, I found my local IP address and subnet range using the ifconfig command. Based on the IP range, I ran a TCP SYN scan using the command nmap -sS 172.17.144.0/20. This allowed me to discover devices on the network and the services running on them.

From the scan, I observed several open ports such as 21 (FTP), 80 (HTTP), 135 (MSRPC), 139 (NetBIOS), 443 (HTTPS), 445 (Microsoft-DS), 3306 (MySQL), and others. These ports indicate various services that could be running on the devices found.

After identifying the open ports, I researched the services typically associated with them and noted the possible security risks. For example, FTP on port 21 can be insecure if not configured properly, and MySQL on port 3306 can expose databases if not protected.

Finally, I saved the scan results in a text file and documented my findings. This exercise helped me understand how network scanning tools like Nmap are used in cybersecurity to assess potential vulnerabilities and monitor network activity.
