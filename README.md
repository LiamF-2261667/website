# MYSQL:
Username: admin
Password: rplp3S2moN54

# Docker Image:
tag: liam/cv:latest

docker build -t liam/cv:latest .

docker run -p "8080:80" -v ${PWD}/codeigniter:/app -v ${PWD}/mysql:/var/lib/mysql liam/cv:latest

# Test Data:
Email:						Password:
