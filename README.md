# owncloud
Steps - own cloud 
	sudo su-
	apt-get install docker -y
	apt-get install docker.io -y
	systemctl docker start
	docker ps 
	service docker start
	docker --version

Google --- install docker compose 
	blue link p click  -- compose standalone 
	1 copy and 2 copy and paste in terminal 
		curl -SL https://github.com/docker/compose/releases/download/v2.27.0/docker-compose-linux-x86_64 -o /usr/local/bin/docker-compose
		sudo ln -s /usr/local/bin/docker-compose /usr/bin/docker-compose
Terminal -- 
	chmod -R 777 /usr/local/bin/docker-compose /usr/bin/docker-compose

Google ---- own cloud with docker 
		copy 2 paragraph in notes and make a folder own cloud server paste it there with name docker-compose.yaml
		copy 3 from 2 line to last 2 line and paste it in notes 

				OWNCLOUD_VERSION=10.14
				OWNCLOUD_DOMAIN=localhost:8080
				OWNCLOUD_TRUSTED_DOMAINS=localhost
				ADMIN_USERNAME=admin
				ADMIN_PASSWORD=admin
				HTTP_PORT=8080
 
Terminal --- ifconfig 
		take the ip inet in last 2 paragraph 192.168.0.___
		and then paste these in notes 3 paragraph in 2 line in place of localhost and in 3 line  and then save these with name .env in own-cloud-server file 
		Then in terminal type that own cloud server document path as -- cd /home/name/own-cloud-server 
		then in terminal ls -l
		then in terminal ls -la
		then docker-compose up -d
		then docker ps 
		

Google  -- localhost:8080/login
	
