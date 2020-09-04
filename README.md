## How to run?

This command will start mysqlserver and phpmyadmin on port 80:

```sh
sudo docker-compose up
```
You can step into mysql client, which is located in a docker container. Type the following command to another terminal window:

```sh
sudo docker-compose exec mysqlserver mysql -u root -proot testdb
```sh

