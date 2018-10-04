This is a simple python 3 script to search through whichever file logs ssh failed attemps and basically pulls the IP addresses from those lines and prints them to screen with the number of times each IP has attempted connection.
It's just an easy way for me to scan through logs to find IPs that are hitting my server slow enough to avoid fail2ban/my-eyes detection.
