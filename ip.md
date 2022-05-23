## ip interface 
stat check 
```
ubunter@u-iron-153552:~$ ip -s -c addr sh dev cscotun0
```

5: cscotun0: <POINTOPOINT,MULTICAST,NOARP,UP,LOWER_UP> mtu 1406 qdisc fq_codel state UNKNOWN group default qlen 500
    link/none 
    inet 192.168.16.150/24 brd 192.168.16.255 scope global cscotun0
       valid_lft forever preferred_lft forever
    inet6 fe80::8c23:3703:404a:5219/126 scope link 
       valid_lft forever preferred_lft forever
    inet6 fe80::348b:1776:6773:87ae/64 scope link stable-privacy 
       valid_lft forever preferred_lft forever
    RX: bytes  packets  errors  dropped overrun mcast   
    25442447   73318    0       0       0       0       
    TX: bytes  packets  errors  dropped carrier collsns 
    6275055    78766    0       0       0       0
