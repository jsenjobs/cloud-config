配置服务器


network sub003

docker build -t jsenht/spring-config:1.0.1 .

docker run -d --name js-config --network=sub003 jsenht/spring-config:1.0.1
docker run -d -p 8082:8082 --name js-config --network=sub003 jsenht/spring-config:1.0.1
