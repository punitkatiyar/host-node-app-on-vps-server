# host-mern-app-vps-server
step by step  guide to setup mern app on vps server

## Setup Nginx On VPS Server 

> pwd : root

> sudo apt update

> sudo apt upgrade -y

> sudo apt install nginx -y

> sudo systemctl start nginx

> sudo systemctl enable nginx

## Default Web Directory

> var/www/html/index.nginx-debian.html

## Setup node js and npm 

> curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.7/install.sh | bash

> nvm install node

> nvm install --lts

> node -v

> npm -v  
