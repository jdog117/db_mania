# Sandbox for testing and improving db skills

### Database connection
#### Sakila db in Docker
docker run -p 3306:3306 -d sakiladb/mysql:latest

Other db info: https://github.com/sakiladb/mysql

#### MySQL db in Docker
docker run -p 3306:3306 -d mysql:latest

Connect: mysql -h 172.17.0.2 -u root -p