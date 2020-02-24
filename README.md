# docker-compose_demo
Simple docker-compose demo: create a server and client

```shell
docker-compose up --build
```



Tips:

+ Default network setting of container is bridge, every container can access each other. We don't even need to EXPOSE port
+ The url is the name of "services" in docker-compose.yml