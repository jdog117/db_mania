# Sandbox for testing and improving database skills

### Database connection
#### Sakila db in Docker
docker run -p 3306:3306 -d sakiladb/mysql:latest

Other db info: https://github.com/sakiladb/mysql

#### MySQL db in Docker
docker run -p 3306:3306 -d mysql:latest

Connect: mysql -h 172.17.0.2 -u root -p

#### Users
> CREATE USER 'your_username'@'your_host' IDENTIFIED BY 'your_password';
> GRANT ALL PRIVILEGES ON your_database.* TO 'your_username'@'your_host';

## ToDo
- [ ] Create some db migrations
- [ ] Implement Prisma
- [ ] js sequalize
- [ ] py alchemy
