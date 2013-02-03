pinfo
=====

Process Info - Run pinfo and provide either a process id or search string. The script will return various useful information
such as amount of children, how long the pids have been running for, cpu/mem usage, tcp listen ports and lots more.. refer to output below for an example:



###Examples of either pid or text given after command and its output..


## pinfo  apache2


7088 IS A MASTER PID, WITH 5 CHILDREN : 7092 7093 7094 7095 7096| Running time: 2 minutes| TEXT: /usr/lib/apache2/mpm-prefork/apache2 | DIRECTORY: / | TCP PORTS: *:80 *:443| PROCESS NAME: /usr/sbin/apache2 | CPU USED: 0.0 | MEM USED: 0.0\n
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



###expanding - ESTABLISED CONNECTIONS BY USING -e -p pid or -e -s search string
##./pinfo -e  -p 9560




9560 IS A MASTER PID, WITH 4 CHILDREN : 21843 21846 21848 21856| Running time: 3 hours| TEXT: | DIRECTORY: | TCP PORTS: *:8080 *:8009 localhost:8005 | ESTABLISHED: 28| PROCESS NAME: /usr/lib/jvm/java-6-sun/jre//bin/java | CPU USED: 30.6 | MEM USED: 48.01 TCP:localhost:40050->localhost:3306

2 TCP:localhost:8009->localhost:55861

3 TCP:localhost:39717->localhost:3306

4 TCP:localhost:8009->localhost:55864

5 TCP:localhost:8009->localhost:55868

6 TCP:localhost:8009->localhost:55873

7 TCP:localhost:8009->localhost:55880

8 TCP:localhost:40051->localhost:3306

9 TCP:localhost:8009->localhost:55883

10 TCP:localhost:8009->localhost:55884

11 TCP:localhost:8009->localhost:55885

12 TCP:localhost:8009->localhost:55886

13 TCP:localhost:8009->localhost:55887

14 TCP:localhost:8009->localhost:42133

15 TCP:localhost:40252->localhost:3306

16 TCP:localhost:8009->localhost:57199

17 TCP:localhost:8009->localhost:34907

18 TCP:localhost:8009->localhost:34494

19 TCP:localhost:8009->localhost:47211

20 TCP:localhost:8009->localhost:56187

21 TCP:localhost:8009->localhost:45185

22 TCP:localhost:8009->localhost:54360

23 TCP:localhost:8009->localhost:44337

24 TCP:localhost:8009->localhost:49434

25 TCP:localhost:8009->localhost:49587

26 TCP:localhost:8009->localhost:47427

27 TCP:localhost:8009->localhost:43669

28 TCP:localhost:8009->localhost:51389

| Running time: ERR: could not locate /proc/21843



##./pinfo 9560




9560 IS A MASTER PID, WITH 0 CHILDREN :| Running time: 3 hours| TEXT: | DIRECTORY: | TCP PORTS: *:8080 *:8009 localhost:8005 | ESTABLISHED: 32| PROCESS NAME: /usr/lib/jvm/java-6-sun/jre//bin/java | CPU USED: 30.6 | MEM USED: 47.2

