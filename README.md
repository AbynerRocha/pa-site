- docker run --name=myqsl -p3306:3306 -v=mysql-volume:/var/lib/mysql -e MYSQL_ROOT_HOST='%' -e MYSQL_ROOT_PASSWORD='passroot' -d mysql/mysql-server:latest