Port Scanner and Banner Grabbing
Description

This repository contains two Python scripts for network scanning:

  portscanner.py
  Simple script for conducting a basic port scan on a specified IP address within a given port range.
        Utilizes the socket module to check for open or closed ports.
        Example output:


      
         1 : closed
         2 : closed
         3 : closed
        ...
        80 : open
        81 : closed
        ...


bannergrabbing.py

  Script for conducting a port scan with an additional attempt to grab banners from open ports.
    Utilizes the socket module and includes a timeout for connection attempts.
    If a port is open, it tries to retrieve the banner information.
    Example output:


     1 : use different method
     2 : use different method
     3 : use different method
    ...
     80 : open : Banner : HTTP/1.1 200 OK
    ...




  Usage


Clone the repository:

     git clone https://github.com/your-username/network-scanner.git
     cd network-scanner


  Update the ip variable in the scripts with the target IP address.
Run the scripts:


    python portscanner.py
    python bannergrabbing.py


Enjoy it!





    
