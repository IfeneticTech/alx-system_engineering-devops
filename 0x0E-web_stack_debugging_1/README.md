# Web Stack Debugging #1

This was the second project in a series of web stack debugging projects. In these
projects, I was given broken/bugged webstacks in particular isolated containers,
and tasked with fixing the web stack to a normal working state. For each
given task, I wrote a script automating the commands necessary to fix the
web stack issue.

## Tasks :page_with_curl:

* **0. Nginx likes port 80**
  * [0-nginx_likes_port_80](./0-nginx_likes_port_80): Bash script that
  configures Nginx to run and listen to port 80 on all of a server's active IPv4's.

* **1. Make it sweet and short**
  * [1-debugging_made_short](./1-debugging_made_short): Bash script that
  configures Nginx to listen to port 80 without running on all of a server's
  active IPv4's.
