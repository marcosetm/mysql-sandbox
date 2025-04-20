## mysql-sandbox
Sandbox for MySQL.

### Running
Copy `dev.env` to `.env`
```bash
cp dev.env .evn
```
Update your `root` user password in `.env`
```
MYSQL_ROOT_PASSWORD=some-password-here
```
Run `docker-compose`
```bash
docker-compose up
```

### Connect Workbench
Download [MySQL Workbench](https://www.mysql.com/products/workbench/) then create a new connection with:
```
Connection Name: mysql-docker-connection-name-you-choose
Hostname: 127.0.0.1
Port: 3306
Username: root
Password: {whatever you set in the .env file}
```