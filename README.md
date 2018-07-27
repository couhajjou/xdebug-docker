## Intro

A simple php project on docker to test xdebug

## Xdebug setup

You can use the command ```docker ps``` and the command ```docker inspect``` to get the container IP

Then, make sure that the firewall is not blocking the connection from xdebug to the IDE

    c_ouhajjou@mtl1-w-pc-07316:~/Repos/xdebug-docker$ sudo ufw status
    [sudo] password for c_ouhajjou: 
    Status: active

    To                         Action      From
    --                         ------      ----
    9000                       ALLOW       172.16.0.0/12              (log)

## Resources
- ufw: firewall manager for linux
- gufw: You can use gufw is gui tool to manage ufw rules.
- [rfc1918: Address Allocation for Private Internets](https://tools.ietf.org/html/rfc1918)

