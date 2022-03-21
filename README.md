## Setup Nginx with Docker Container and Auto Renew Let's encrypt SSL
\\
Before we start installing and configuring Nginx please edit 'init-letsencrypt.sh' file and change domain name, after that add record to your DNS Management with your 'ip server' excample server public ip is 10.10.1.132 and domain name **api.anwar.com** add your subdomain on DNS management with your server ip.

* Run 'init-letsencrypt.sh' file './init-letsencrypt.sh' or 'bash ./init-letsencrypt.sh'
* Run 'docker-compose.yml' file with this command 'docker-compose up -d'
* edit config file 'data/nginx/server_block.conf'# nginx-docker-autossl
