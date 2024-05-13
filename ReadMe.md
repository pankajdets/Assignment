//MYSQL Docker setup

docker pull mysql
docker run --name=mysql1 -p 3307:3306 -e MYSQL_ROOT_PASSWORD=amit -d mysql
docker exec -it mysql1 mysql -uroot -p


