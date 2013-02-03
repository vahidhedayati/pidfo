pinfo
=====

Process Info - This gives a given pid or maps search string to a pid and returns amount of children and how long specific child and its parent or master pid has been running for 


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



