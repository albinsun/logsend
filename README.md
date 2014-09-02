logsend
=========

the stupid syslog sender

```
usage: logsend [-h] [-f EPS] [-n N] [-p PRIORITY] [-s SERVER] [-v] [-i FILE]
               [message]

the stupid syslog sender

positional arguments:
  message               message by text

optional arguments:
  -h, --help            show this help message and exit
  -f EPS, --eps EPS     events per second (eps)
  -n N, --number N      send N events, -1 for endless
  -p PRIORITY, --priority PRIORITY
                        syslog priority (facility.severity)
  -s SERVER, --server SERVER
                        send to syslog server SERVER
  -v, --version         show program's version number and exit
  -i FILE, --file FILE  message by file content

https://github.com/ypsun/logsend
```
