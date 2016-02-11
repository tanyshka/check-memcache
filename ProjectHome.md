This is a plugin for NAGIOS developed in PHP. You need to install php-memcache, and php >= 4.3.3

It returns all the memcache extended status for nagios perfdata. To get some help, run check\_memcached --help.

Returns:

MEMCACHED\_OK\_MSG - 0.001s | pid=2785, uptime=70445, time=1270115881, version=1.2.8, pointer\_size=64, rusage\_user=0.000000, rusage\_system=0.000000, curr\_items=0, total\_items=0, bytes=0, curr\_connections=5, total\_connections=70, connection\_structures=6, cmd\_flush=0, cmd\_get=0, cmd\_set=0, get\_hits=0, get\_misses=0, evictions=0, bytes\_read=455, bytes\_written=34692, limit\_maxbytes=67108864, threads=5, accepting\_conns=1, listen\_disabled\_num=0