# docker-guide

FROM shubhamtatvamasi/rohit-first-image

RUN echo "rohit is very good hello" > /usr/share/nginx/html/index.html

```bash
docker pull shubhamtatvamasi/rohit-first-image


docker ps
docker ps -a
docker build -t rohitsecond .

docker run -it -p 80:80 rohitsecond         # create contaionter from images --- fresh 
docker images
docker tag rohitsecond rohitarora7/rohit-second-new-name
docker push rohitarora7/rohit-second-new-name


docker rm -f practical_herschel # in running containter



docker run --name some-mysql -e MYSQL_ROOT_PASSWORD=root -d -p 3306:3306 mysql\

```

`-d` demon 

`-e` environment 

80:80 aage:piche


```
docker run --name mysql -e MYSQL_ROOT_PASSWORD=password -d mysql
docker rm -f mysql
docker logs mysql -f
docker top

docker exec -it mysql mysql -ppassword
```
