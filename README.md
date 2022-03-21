# Vehicle Service
Vehicle service endpoint.

## Tasks
- Navigate to Spring Boot Initializer website -> https://start.spring.io/ 
- Fill up your application package information, with following plugins added onto it:-
    - Lombok
    - Jersey
    - Spring Boot DevTools
    - Spring Web 
    - Rest Repositories 
    - Flyway Migration 
    - JOOQ Access Layer 
    - MariaDB Driver
- Download the package, extract the content and import into IntelliJ IDE.
- Open pom.xml file.
- Comment following code segment.
    ```
        <!-- <dependency>
            <groupId>org.springframework.boot</groupId>
            <artifactId>spring-boot-starter-jooq</artifactId>
		</dependency>

        <dependency>
			<groupId>org.mariadb.jdbc</groupId>
			<artifactId>mariadb-java-client</artifactId>
			<scope>runtime</scope>
		</dependency> -->
    ```
- Save the configuration to pom.xml file.
- Open application test loader class at /src/main/test/java/my.com.tcsens.vehiclemanagement/VehicleManagementApplicationTests.java
- Comment contextLoads() method to disable the unit test loader.
    ```
    //	@Test
    //	void contextLoads() {
    //	}
    ```


### Notes:
- Configure IntelliJ SDK project path to JDK 8 home path.
- Run '.\mvnw clean install' to install necessary package defined in pom.xml
- Run '.\mvnw spring-boot:run' to start the Spring Boot application.
