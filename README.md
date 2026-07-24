# Personal Blog Web Application

This project is currently generated for Spring Boot 4.1.0 with Java 21.

Most Spring Boot 3 tutorial code will still be close, but use the Spring Boot 4 dependency names already present in this project. The current MVC setup is:

```xml
<dependency>
	<groupId>org.springframework.boot</groupId>
	<artifactId>spring-boot-starter-webmvc</artifactId>
</dependency>

<dependency>
	<groupId>org.springframework.boot</groupId>
	<artifactId>spring-boot-starter-webmvc-test</artifactId>
	<scope>test</scope>
</dependency>
```

## Run

```bash
./mvnw spring-boot:run
```

## Test

```bash
./mvnw test
```

## Spring Boot 3 Tutorial Notes

When a tutorial says to add `spring-boot-starter-web`, keep this project's `spring-boot-starter-webmvc` dependency instead. See [SPRING_BOOT_4_MIGRATION.md](SPRING_BOOT_4_MIGRATION.md) for the local Boot 3-to-4 translation notes.
