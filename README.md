# sharpt
Show ARP table interface eth0

Install
1. Copy ShowARPtable.sh to /root/
2. Add to crontab:
    */1 * * * * /root/ShowARPtable.sh > /dev/console
