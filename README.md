# Vehicle Service
Vehicle service endpoint.

## Tasks

- Copy **pom.xml** from the repository and place it at your local workspace.
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
- Save the configuration to **pom.xml** file.
- Copy **settings.xml** from the repository, and store it at <user_dir>/.m2/ folder.
  (e.g.: C:\Users\justin.phua\.m2\)
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
