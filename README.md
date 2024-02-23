# Desafio Capitole - Zara

**Getting Started**
* Java 17
* Spring Boot
* Junit 5
* Lombok
* H2
* Jpa - Hibernate

### HTTP Operation that exposes our API

| Path | Operation | Summary               |
| ------ | ------ |-----------------------|
|/product/35455?brandId=1&date=2020-06-16 21:00:00|GET| Get Product Detail |

### For swagger document
http://localhost:8080/swagger-ui/index.html

### Prepare project 
mvn clean install

### run project 
cd infrastructure
mvn spring-boot:infrastructure:run