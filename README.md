# Eureka and Addons
Eureka server and API gateway for microservices

These were the part of the project but later removed from the dependencies to keep the things in control.

> # Following can be added anytime
- Eureka Server
- Eureka Client
- Google OAuth2 or JWT for authentication/authorization
- Log4j
- Actuator end points

> # Few removed dependencies that can be added

<dependency>
		<groupId>org.springframework.boot</groupId>
		<artifactId>spring-boot-starter-oauth2-client</artifactId>
</dependency>

<dependency>
    <groupId>org.apache.logging.log4j</groupId>
    <artifactId>log4j-api</artifactId>
    <version>2.11.2</version>
</dependency>

<dependency>
    <groupId>org.apache.logging.log4j</groupId>
    <artifactId>log4j-core</artifactId>
    <version>2.11.2</version>
</dependency>

<dependency>
			<groupId>org.springframework.boot</groupId>
			<artifactId>spring-boot-starter-actuator</artifactId>
</dependency>
<dependency>
			<groupId>org.springframework.boot</groupId>
			<artifactId>spring-boot-starter-security</artifactId>
</dependency>
