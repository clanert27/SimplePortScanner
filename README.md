# SimplePortScanner
What is Port Scanner ? 

A port scanner is a computer program that checks network ports for one of three possible statuses – open, closed, or filtered.  Port scanners are valuable tools in diagnosing network and connectivity issues. However, attackers use port scanners to detect possible access points for infiltration and to identify what kinds of devices you are running on the network, like firewalls, proxy servers or VPN servers. 

How Does a Port Scanner Works?  
A port scanner sends a network request to connect to a specific TCP or UDP port on a computer and records the response.  So what a port scanner does is send a packet of network data to a port to check the current status. If you wanted to check to see if your web server was operating correctly, you would check the status of port 80 on that server to make sure it was open and listening.  The status helps network engineers diagnose network issues or application connectivity issues, or helps attackers find possible ports to use for infiltration into your network.

HOW TO RUN? `python3`
* Clone the repository into the linux/windows system
* Run the requirements.txt file
* Use the following syntax to run the 'portscanner.py' file:
    `python3 portscanner.py [TARGET IP ADDRESS]`
    
  Example:
  `python3 portscanner.py 192.168.0.148`

![image](https://user-images.githubusercontent.com/64724214/139826007-d6165482-b730-462e-a9d1-0e437bfc4dbe.png)
