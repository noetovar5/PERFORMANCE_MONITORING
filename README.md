<img align="right" src="https://visitor-badge.laobi.icu/badge?page_id=noetovar5.PERFORMANCE_MONITORING"/>
##PERFORMANCE_MONITORING
PERFORMANCE MONITORING for Linux Administrators

Display and manage the top processes
top

* 💻Interactive process viewer (top alternative)
htop

* 💻Display processor related statistics
mpstat 1

* 💻Display virtual memory statistics
vmstat 1

* 💻Display I/O statistics
iostat 1

* 💻Display the last 100 syslog messages  (Use /var/log/syslog for Debian based systems.)
tail -100 /var/log/messages

* 💻Capture and display all packets on interface eth0
tcpdump -i eth0

* 💻Monitor all traffic on port 80 ( HTTP )
tcpdump -i eth0 'port 80'

* 💻List all open files on the system
lsof

* 💻List files opened by user
lsof -u user

* 💻Display free and used memory ( -h for human readable, -m for MB, -g for GB.)
free -h

* 💻Execute "df -h", showing periodic updates
watch df -h
