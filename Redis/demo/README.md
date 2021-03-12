# Spring Boot + Redis Demo
Spring Boot Project에서 Redis를 연동하여 각종 다양한 사용법들을 기록하는 공간입니다.

### Environment
```
* Spring Boot 2.4.3
* Open JDK Zulu-1.8
* Docker
```

### Docker에 Redis Server 생성하는 방법을 알아봅시다
* ✔ Docker를 사용하고 있어야 합니다.
* redis container 생성 👉 docker run -p 6379:6379 --name redis -d redis
* redis-cli 👉 docker run -it --link redis:redis --rm redis redis-cli -h redis -p 6379
