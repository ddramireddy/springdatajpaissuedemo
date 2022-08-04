# springdatajpaissuedemo


This project is demo project to show Transaction rollback issue in Spring Data JPA library from 2.5.6 onwards. Changing the dependency to less than 2.5.5 shows project is successful.

```
<dependency>
            <groupId>org.springframework.data</groupId>
            <artifactId>spring-data-jpa</artifactId>
            <version>2.5.6</version>
        </dependency>
```       
        
        
        
        
This project needs Postgresql to be installed on Localhost 5432 port. Database name, username and password should be "postgres". These can be updated in DatabaseConfig.java file under the directory: src/main/java/com/example/demo/config 
        
        
