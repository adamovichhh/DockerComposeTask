App1-3:
 - app1-3.py - simple Python Flask scripts
 - requirements.txt - contain only the flask library since we are using the python3 image
 - Dockerfile - it's for creating application container

nginx.conf - congiguration of nginx fot it container.  
Dockerfile - it's for creating container based on nginx.    
docker-compose.yml - for multicontainer environment.

To run docker-compose:
`docker compose up --build -d`  
