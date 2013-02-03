pinfo
=====

Process Info - Run pinfo and provide either a process id or search string. The script will return various useful information
such as amount of children, how long the pids have been running for, cpu/mem usage, tcp listen ports and lots more.. refer to output below for an example:



###Examples of either pid or text given after command and its output..


## pinfo  apache2


7088 IS A MASTER PID, WITH 5 CHILDREN : 7092 7093 7094 7095 7096| Running time: 2 minutes| TEXT: /usr/lib/apache2/mpm-prefork/apache2 | DIRECTORY: / | TCP PORTS: *:80 *:443| PROCESS NAME: /usr/sbin/apache2 | CPU USED: 0.0 | MEM USED: 0.0

7092 IS A CHILD PID OF 7088| Running time: 2 minutes| TEXT: /usr/lib/apache2/mpm-prefork/apache2 | DIRECTORY: | TCP PORTS: *:80 *:443| PROCESS NAME: /usr/sbin/apache2 | CPU USED: 0.0 | MEM USED: 0.0

7093 IS A CHILD PID OF 7088| Running time: 2 minutes| TEXT: /usr/lib/apache2/mpm-prefork/apache2 | DIRECTORY: | TCP PORTS: *:80 *:443| PROCESS NAME: /usr/sbin/apache2 | CPU USED: 0.0 | MEM USED: 0.0

7094 IS A CHILD PID OF 7088| Running time: 2 minutes| TEXT: /usr/lib/apache2/mpm-prefork/apache2 | DIRECTORY: | TCP PORTS: *:80 *:443| PROCESS NAME: /usr/sbin/apache2 | CPU USED: 0.0 | MEM USED: 0.0

7095 IS A CHILD PID OF 7088| Running time: 2 minutes| TEXT: /usr/lib/apache2/mpm-prefork/apache2 | DIRECTORY: | TCP PORTS: *:80 *:443| PROCESS NAME: /usr/sbin/apache2 | CPU USED: 0.0 | MEM USED: 0.0

7096 IS A CHILD PID OF 7088| Running time: 2 minutes| TEXT: /usr/lib/apache2/mpm-prefork/apache2 | DIRECTORY: | TCP PORTS: *:80 *:443| PROCESS NAME: /usr/sbin/apache2 | CPU USED: 0.0 | MEM USED: 0.0



## pinfo  7088




7088 IS A MASTER PID, WITH 5 CHILDREN : 7092 7093 7094 7095 7096| Running time: 2 minutes| TEXT: /usr/lib/apache2/mpm-prefork/apache2 | DIRECTORY: / | TCP PORTS: *:80 *:443| PROCESS NAME: /usr/sbin/apache2 | CPU USED: 0.0 | MEM USED: 0.0

7092 IS A CHILD PID OF 7088| Running time: 2 minutes| TEXT: /usr/lib/apache2/mpm-prefork/apache2 | DIRECTORY: | TCP PORTS: *:80 *:443| PROCESS NAME: /usr/sbin/apache2 | CPU USED: 0.0 | MEM USED: 0.0

7093 IS A CHILD PID OF 7088| Running time: 2 minutes| TEXT: /usr/lib/apache2/mpm-prefork/apache2 | DIRECTORY: | TCP PORTS: *:80 *:443| PROCESS NAME: /usr/sbin/apache2 | CPU USED: 0.0 | MEM USED: 0.0

7094 IS A CHILD PID OF 7088| Running time: 2 minutes| TEXT: /usr/lib/apache2/mpm-prefork/apache2 | DIRECTORY: | TCP PORTS: *:80 *:443| PROCESS NAME: /usr/sbin/apache2 | CPU USED: 0.0 | MEM USED: 0.0

7095 IS A CHILD PID OF 7088| Running time: 2 minutes| TEXT: /usr/lib/apache2/mpm-prefork/apache2 | DIRECTORY: | TCP PORTS: *:80 *:443| PROCESS NAME: /usr/sbin/apache2 | CPU USED: 0.0 | MEM USED: 0.0

7096 IS A CHILD PID OF 7088| Running time: 2 minutes| TEXT: /usr/lib/apache2/mpm-prefork/apache2 | DIRECTORY: | TCP PORTS: *:80 *:443| PROCESS NAME: /usr/sbin/apache2 | CPU USED: 0.0 | MEM USED: 0.0



## pinfo  7094




7094 IS A CHILD PID OF 7088| Running time: 2 minutes| TEXT: /usr/lib/apache2/mpm-prefork/apache2 | DIRECTORY: | TCP PORTS: *:80 *:443| PROCESS NAME: /usr/sbin/apache2 | CPU USED: 0.0 | MEM USED: 0.0

7088 IS A MASTER PID, WITH 5 CHILDREN : 7092 7093 7094 7095 7096| Running time: 2 minutes| TEXT: /usr/lib/apache2/mpm-prefork/apache2 | DIRECTORY: / | TCP PORTS: *:80 *:443| PROCESS NAME: /usr/sbin/apache2 | CPU USED: 0.0 | MEM USED: 0.0





#time pinfo 1




1 IS A SYSTEM PID, WITH 56 CHILD PIDS: 404 463 735 975 982 994 1017 1020 1119 1166 1170 1192 1199 1203 1274 1279 1285 1286 1289 1319 1320 1321 1322 1324 1330 1404 1633 1763 1891 1892 1920 1952 1953 1956 1960 1962 1966 1968 2146 2148 2154 2159 2188 2208 2219 2221 2223 2234 2242 2249 2254 2258 2261 2267 2408 7088| Running time: 37 minutes| TEXT: /sbin/init | DIRECTORY: / | TCP PORTS:| PROCESS NAME: /sbin/init | CPU USED: 0.0 | MEM USED: 0.0

404 IS A MASTER PID, WITH 0 CHILDREN :| Running time: 37 minutes| TEXT: /sbin/upstart-udev-bridge | DIRECTORY: / | TCP PORTS:| PROCESS NAME: upstart-udev-bridge | CPU USED: 0.0 | MEM USED: 0.0

463 IS A MASTER PID, WITH 2 CHILDREN : 628 629| Running time: 37 minutes| TEXT: /sbin/udevd | DIRECTORY: / | TCP PORTS:| PROCESS NAME: /sbin/udevd | CPU USED: 0.0 | MEM USED: 0.0

735 IS A MASTER PID, WITH 0 CHILDREN :| Running time: 37 minutes| TEXT: /sbin/upstart-socket-bridge | DIRECTORY: / | TCP PORTS:| PROCESS NAME: upstart-socket-bridge | CPU USED: 0.0 | MEM USED: 0.0

975 IS A MASTER PID, WITH 0 CHILDREN :| Running time: 37 minutes| TEXT: /bin/dbus-daemon | DIRECTORY: | TCP PORTS:| PROCESS NAME: dbus-daemon | CPU USED: 0.0 | MEM USED: 0.0

982 IS A MASTER PID, WITH 0 CHILDREN :| Running time: 37 minutes| TEXT: /usr/sbin/rsyslogd | DIRECTORY: | TCP PORTS:| PROCESS NAME: rsyslogd | CPU USED: 0.0 | MEM USED: 0.0

994 IS A MASTER PID, WITH 0 CHILDREN :| Running time: 37 minutes| TEXT: /usr/sbin/bluetoothd | DIRECTORY: / | TCP PORTS:| PROCESS NAME: /usr/sbin/bluetoothd | CPU USED: 0.0 | MEM USED: 0.0

1017 IS A MASTER PID, WITH 1 CHILDREN : 1018| Running time: 37 minutes| TEXT: /usr/sbin/avahi-daemon | DIRECTORY: | TCP PORTS:| PROCESS NAME: avahi-daemon: | CPU USED: 0.0 | MEM USED: 0.0

1020 IS A MASTER PID, WITH 0 CHILDREN :| Running time: 37 minutes| TEXT: /usr/sbin/cupsd | DIRECTORY: / | TCP PORTS: ip6-localhost:631 localhost:631| PROCESS NAME: /usr/sbin/cupsd | CPU USED: 0.0 | MEM USED: 0.0

1119 IS A MASTER PID, WITH 0 CHILDREN :| Running time: 37 minutes| TEXT: /sbin/dhclient | DIRECTORY: / | TCP PORTS:| PROCESS NAME: dhclient3 | CPU USED: 0.0 | MEM USED: 0.0

1166 IS A MASTER PID, WITH 1 CHILDREN : 2776| Running time: 37 minutes| TEXT: /usr/sbin/sshd | DIRECTORY: / | TCP PORTS: *:22 *:22| PROCESS NAME: /usr/sbin/sshd | CPU USED: 0.0 | MEM USED: 0.0

1170 IS A MASTER PID, WITH 0 CHILDREN :| Running time: 37 minutes| TEXT: /usr/bin/mediatomb | DIRECTORY: | TCP PORTS: *:49152| PROCESS NAME: mediatomb | CPU USED: 0.0 | MEM USED: 0.8

1192 IS A MASTER PID, WITH 0 CHILDREN :| Running time: 37 minutes| TEXT: /usr/sbin/modem-manager | DIRECTORY: / | TCP PORTS:| PROCESS NAME: /usr/sbin/modem-manager | CPU USED: 0.0 | MEM USED: 0.0

1199 IS A MASTER PID, WITH 0 CHILDREN :| Running time: 37 minutes| TEXT: /usr/sbin/NetworkManager | DIRECTORY: / | TCP PORTS:| PROCESS NAME: NetworkManager | CPU USED: 0.0 | MEM USED: 0.1

1203 IS A MASTER PID, WITH 0 CHILDREN :| Running time: 37 minutes| TEXT: /usr/lib/policykit-1/polkitd | DIRECTORY: / | TCP PORTS:| PROCESS NAME: /usr/lib/policykit-1/polkitd | CPU USED: 0.0 | MEM USED: 0.0

1274 IS A MASTER PID, WITH 0 CHILDREN :| Running time: 37 minutes| TEXT: /sbin/getty | DIRECTORY: / | TCP PORTS:| PROCESS NAME: /sbin/getty | CPU USED: 0.0 | MEM USED: 0.0

1279 IS A MASTER PID, WITH 0 CHILDREN :| Running time: 37 minutes| TEXT: /sbin/getty | DIRECTORY: / | TCP PORTS:| PROCESS NAME: /sbin/getty | CPU USED: 0.0 | MEM USED: 0.0

1285 IS A MASTER PID, WITH 0 CHILDREN :| Running time: 37 minutes| TEXT: /sbin/getty | DIRECTORY: / | TCP PORTS:| PROCESS NAME: /sbin/getty | CPU USED: 0.0 | MEM USED: 0.0

1286 IS A MASTER PID, WITH 0 CHILDREN :| Running time: 37 minutes| TEXT: /sbin/getty | DIRECTORY: / | TCP PORTS:| PROCESS NAME: /sbin/getty | CPU USED: 0.0 | MEM USED: 0.0

1289 IS A MASTER PID, WITH 0 CHILDREN :| Running time: 37 minutes| TEXT: /sbin/getty | DIRECTORY: / | TCP PORTS:| PROCESS NAME: /sbin/getty | CPU USED: 0.0 | MEM USED: 0.0

1319 IS A MASTER PID, WITH 0 CHILDREN :| Running time: 37 minutes| TEXT: /usr/sbin/acpid | DIRECTORY: / | TCP PORTS:| PROCESS NAME: acpid | CPU USED: 0.0 | MEM USED: 0.0

1320 IS A MASTER PID, WITH 0 CHILDREN :| Running time: 37 minutes| TEXT: /usr/sbin/cron | DIRECTORY: /var/spool/cron | TCP PORTS:| PROCESS NAME: cron | CPU USED: 0.0 | MEM USED: 0.0

1321 IS A MASTER PID, WITH 0 CHILDREN :| Running time: 37 minutes| TEXT: /usr/sbin/atd | DIRECTORY: | TCP PORTS:| PROCESS NAME: atd | CPU USED: 0.0 | MEM USED: 0.0

1322 IS A MASTER PID, WITH 2 CHILDREN : 1356 1651| Running time: 37 minutes| TEXT: /usr/bin/kdm | DIRECTORY: / | TCP PORTS:| PROCESS NAME: kdm | CPU USED: 0.0 | MEM USED: 0.0

1324 IS A MASTER PID, WITH 0 CHILDREN :| Running time: 37 minutes| TEXT: /usr/sbin/irqbalance | DIRECTORY: / | TCP PORTS:| PROCESS NAME: /usr/sbin/irqbalance | CPU USED: 0.0 | MEM USED: 0.0

1330 IS A MASTER PID, WITH 0 CHILDREN :| Running time: 37 minutes| TEXT: /usr/sbin/mysqld | DIRECTORY: | TCP PORTS: localhost:3306| PROCESS NAME: /usr/sbin/mysqld | CPU USED: 0.0 | MEM USED: 1.0

1404 IS A MASTER PID, WITH 1 CHILDREN : 1452| Running time: 37 minutes| TEXT: /usr/sbin/winbindd | DIRECTORY: / | TCP PORTS:| PROCESS NAME: /usr/sbin/winbindd | CPU USED: 0.0 | MEM USED: 0.0

1633 IS A MASTER PID, WITH 0 CHILDREN :| Running time: 36 minutes| TEXT: /sbin/getty | DIRECTORY: / | TCP PORTS:| PROCESS NAME: /sbin/getty | CPU USED: 0.0 | MEM USED: 0.0

1763 IS A MASTER PID, WITH 0 CHILDREN :| Running time: 37 minutes| TEXT: /usr/sbin/console-kit-daemon | DIRECTORY: / | TCP PORTS:| PROCESS NAME: /usr/sbin/console-kit-daemon | CPU USED: 0.0 | MEM USED: 0.0

1891 IS A MASTER PID, WITH 0 CHILDREN :| Running time: 37 minutes| TEXT: /usr/bin/dbus-launch | DIRECTORY: | TCP PORTS:| PROCESS NAME: /usr/bin/dbus-launch | CPU USED: 0.0 | MEM USED: 0.0

1892 IS A MASTER PID, WITH 0 CHILDREN :| Running time: 36 minutes| TEXT: /bin/dbus-daemon | DIRECTORY: | TCP PORTS:| PROCESS NAME: //bin/dbus-daemon | CPU USED: 0.0 | MEM USED: 0.0

1920 IS A MASTER PID, WITH 1 CHILDREN : 1921| Running time: 37 minutes| TEXT: /usr/lib/udisks/udisks-daemon | DIRECTORY: / | TCP PORTS:| PROCESS NAME: /usr/lib/udisks/udisks-daemon | CPU USED: 0.0 | MEM USED: 0.0

1952 IS A MASTER PID, WITH 0 CHILDREN :| Running time: 36 minutes| TEXT: /usr/lib/kde4/libexec/start_kdeinit | DIRECTORY: | TCP PORTS:| PROCESS NAME: /usr/lib/kde4/libexec/start_kdeinit | CPU USED: 0.0 | MEM USED: 0.0

1953 IS A MASTER PID, WITH 10 CHILDREN : 1954 2106 2194 2196 2205 2214 2404 2454 2534 9747| Running time: 37 minutes| TEXT: /usr/bin/kdeinit4 | DIRECTORY: | TCP PORTS:| PROCESS NAME: kdeinit4: | CPU USED: 0.0 | MEM USED: 0.4

1956 IS A MASTER PID, WITH 0 CHILDREN :| Running time: 37 minutes| TEXT: /usr/bin/kdeinit4 | DIRECTORY: | TCP PORTS:| PROCESS NAME: kdeinit4: | CPU USED: 0.0 | MEM USED: 0.6

1960 IS A MASTER PID, WITH 0 CHILDREN :| Running time: 37 minutes| TEXT: /usr/bin/kglobalaccel | DIRECTORY: | TCP PORTS:| PROCESS NAME: /usr/bin/kglobalaccel | CPU USED: 0.0 | MEM USED: 0.3

1962 IS A MASTER PID, WITH 0 CHILDREN :| Running time: 37 minutes| TEXT: /usr/bin/kwalletd | DIRECTORY: | TCP PORTS:| PROCESS NAME: /usr/bin/kwalletd | CPU USED: 0.0 | MEM USED: 0.3

1966 IS A MASTER PID, WITH 0 CHILDREN :| Running time: 37 minutes| TEXT: /usr/bin/kactivitymanagerd | DIRECTORY: | TCP PORTS:| PROCESS NAME: /usr/bin/kactivitymanagerd | CPU USED: 0.0 | MEM USED: 0.3

1968 IS A MASTER PID, WITH 0 CHILDREN :| Running time: 37 minutes| TEXT: /usr/lib/upower/upowerd | DIRECTORY: / | TCP PORTS:| PROCESS NAME: /usr/lib/upower/upowerd | CPU USED: 0.0 | MEM USED: 0.0

2146 IS A MASTER PID, WITH 0 CHILDREN :| Running time: 37 minutes| TEXT: /usr/bin/knotify4 | DIRECTORY: | TCP PORTS:| PROCESS NAME: /usr/bin/knotify4 | CPU USED: 0.0 | MEM USED: 0.7

2148 IS A MASTER PID, WITH 1 CHILDREN : 2156| Running time: 37 minutes| TEXT: /usr/bin/plasma-desktop | DIRECTORY: | TCP PORTS:| PROCESS NAME: /usr/bin/plasma-desktop | CPU USED: 7.5 | MEM USED: 2.1

2154 IS A MASTER PID, WITH 0 CHILDREN :| Running time: 37 minutes| TEXT: /usr/bin/kuiserver | DIRECTORY: | TCP PORTS:| PROCESS NAME: /usr/bin/kuiserver | CPU USED: 0.0 | MEM USED: 0.3

2159 IS A MASTER PID, WITH 13 CHILDREN : 2161 2292 2293 2294 2295 2297 2299 2300 2301 2302 2304 2306 2307| Running time: 37 minutes| TEXT: /usr/bin/akonadi_control | DIRECTORY: | TCP PORTS:| PROCESS NAME: /usr/bin/akonadi_control | CPU USED: 0.0 | MEM USED: 0.1

2188 IS A MASTER PID, WITH 0 CHILDREN :| Running time: 37 minutes| TEXT: /usr/bin/kaccess | DIRECTORY: | TCP PORTS:| PROCESS NAME: /usr/bin/kaccess | CPU USED: 0.0 | MEM USED: 0.3

2208 IS A MASTER PID, WITH 0 CHILDREN :| Running time: 37 minutes| TEXT: /usr/bin/krunner | DIRECTORY: | TCP PORTS:| PROCESS NAME: /usr/bin/krunner | CPU USED: 0.0 | MEM USED: 0.8

2219 IS A MASTER PID, WITH 0 CHILDREN :| Running time: 37 minutes| TEXT: /usr/bin/pulseaudio | DIRECTORY: | TCP PORTS:| PROCESS NAME: /usr/bin/pulseaudio | CPU USED: 0.0 | MEM USED: 0.1

2221 IS A MASTER PID, WITH 0 CHILDREN :| Running time: 37 minutes| TEXT: /usr/bin/zeitgeist-daemon | DIRECTORY: | TCP PORTS:| PROCESS NAME: /usr/bin/zeitgeist-daemon | CPU USED: 0.0 | MEM USED: 0.1

2223 IS A MASTER PID, WITH 0 CHILDREN :| Running time: 37 minutes| TEXT: /usr/lib/rtkit/rtkit-daemon | DIRECTORY: | TCP PORTS:| PROCESS NAME: /usr/lib/rtkit/rtkit-daemon | CPU USED: 0.0 | MEM USED: 0.0

2234 IS A MASTER PID, WITH 1 CHILDREN : 2241| Running time: 37 minutes| TEXT: /usr/lib/zeitgeist/zeitgeist-fts | DIRECTORY: | TCP PORTS:| PROCESS NAME: /usr/lib/zeitgeist/zeitgeist-fts | CPU USED: 0.0 | MEM USED: 0.2

2242 IS A MASTER PID, WITH 0 CHILDREN :| Running time: 37 minutes| TEXT: /usr/lib/kde4/libexec/polkit-kde-authentication-agent-1 | DIRECTORY: | TCP PORTS:| PROCESS NAME: /usr/lib/kde4/libexec/polkit-kde-authentication-agent-1 | CPU USED: 0.0 | MEM USED: 0.4

2249 IS A MASTER PID, WITH 0 CHILDREN :| Running time: 37 minutes| TEXT: /usr/lib/gvfs/gvfsd | DIRECTORY: | TCP PORTS:| PROCESS NAME: /usr/lib/gvfs/gvfsd | CPU USED: 0.0 | MEM USED: 0.0

2254 IS A MASTER PID, WITH 0 CHILDREN :| Running time: 37 minutes| TEXT: /usr/bin/akonaditray | DIRECTORY: | TCP PORTS:| PROCESS NAME: /usr/bin/akonaditray | CPU USED: 0.0 | MEM USED: 0.3

2258 IS A MASTER PID, WITH 0 CHILDREN :| Running time: 37 minutes| TEXT: /usr/bin/kmix | DIRECTORY: | TCP PORTS:| PROCESS NAME: /usr/bin/kmix | CPU USED: 0.0 | MEM USED: 0.6

2261 IS A MASTER PID, WITH 0 CHILDREN :| Running time: 37 minutes| TEXT: /usr/bin/nepomukcontroller | DIRECTORY: | TCP PORTS:| PROCESS NAME: /usr/bin/nepomukcontroller | CPU USED: 0.0 | MEM USED: 0.3

2267 IS A MASTER PID, WITH 0 CHILDREN :| Running time: 37 minutes| TEXT: /usr/bin/klipper | DIRECTORY: | TCP PORTS:| PROCESS NAME: /usr/bin/klipper | CPU USED: 0.0 | MEM USED: 0.3

2408 IS A MASTER PID, WITH 0 CHILDREN :| Running time: 37 minutes| TEXT: /usr/lib/i386-linux-gnu/gconf/gconfd-2 | DIRECTORY: | TCP PORTS:| PROCESS NAME: /usr/lib/i386-linux-gnu/gconf/gconfd-2 | CPU USED: 0.0 | MEM USED: 0.0

7088 IS A MASTER PID, WITH 5 CHILDREN : 7092 7093 7094 7095 7096| Running time: 7 minutes| TEXT: /usr/lib/apache2/mpm-prefork/apache2 | DIRECTORY: / | TCP PORTS: *:80 *:443| PROCESS NAME: /usr/sbin/apache2 | CPU USED: 0.0 | MEM USED: 0.0




real  0m3.997s

user	0m0.492s

sys	0m1.596s

