# sharpt
Show ARP table on console every one minute for interface eth0

Install
1. Copy ShowARPtable.sh to /root/
2. Add to crontab:
    */1 * * * * /root/ShowARPtable.sh > /dev/console
