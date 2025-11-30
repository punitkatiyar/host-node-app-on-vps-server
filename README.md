# host-mern-app-vps-server
step by step  guide to setup mern app on vps server

## step 1

> ssh-keygen -f '/root/.ssh/known_hosts' -R 'ip'

> sudo apt update && sudo apt upgrade -y

> sudo apt install nginx -y

> sudo systemctl start nginx

> sudo systemctl enable nginx 
