# LOAD BALANCER SOLUTION WITH NGINX AND SSL/TLS
Apache and Nginx are two major players in the web server business spanning 5 percent of web traffic over the internet, but they are different from each other.

> The main difference between Apache and Nginx lies in their design architecture. Apache uses a process-driven approach and creates a new thread for each request while Nginx uses an event-driven architecture to handle multiple requests within one thread.

Some of the differences between Apache and Nginx include:

|      Apache                                                   |       Nginx                                                   |
| ---------------------------------------------------------     |---------------------------------------------------------------|
| Apache runs on all Unix like systems such as Linux, BSD, etc. as well as completely supports windows | Nginx runs on modern Unix like systems; however it has limited support for Windows.|
| Apache uses a multi-threaded approach to process client requests.|Nginx follows an event-driven approach to serve client requests.|