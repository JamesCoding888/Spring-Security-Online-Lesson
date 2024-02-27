# Spring-Security-Online-Lesson
  > Spring Tool Suite 4 version
  - 4.15.1.RELEASE

  > Marketplace
  - Thymeleaf Plugin for Eclipse 3.0.0

  > pom.xml

              <?xml version="1.0" encoding="UTF-8"?>
              <project xmlns="http://maven.apache.org/POM/4.0.0" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
              	xsi:schemaLocation="http://maven.apache.org/POM/4.0.0 https://maven.apache.org/xsd/maven-4.0.0.xsd">
              	<modelVersion>4.0.0</modelVersion>
              	<parent>
              		<groupId>org.springframework.boot</groupId>
              		<artifactId>spring-boot-starter-parent</artifactId>
              		<!-- v2.6.3 resolving v3.2.2 without 'org.springframework.security.config.annotation.web.configuration.WebSecurityConfigurerAdapter' -->
              		<!-- <version>3.2.2</version> -->
              		<version>2.6.3</version>
              		<relativePath/> <!-- lookup parent from repository -->
              	</parent>
              	<groupId>com.example</groupId>
              	<artifactId>Spring-Security-Onlin-Lesson</artifactId>
              	<version>0.0.1-SNAPSHOT</version>
              	<packaging>war</packaging>
              	<name>Spring-Security-Onlin-Lesson</name>
              	<description>Demo project for Spring Boot</description>
              	<properties>
              		<java.version>17</java.version>
              	</properties>
              	<dependencies>
              		<dependency>
              			<groupId>org.springframework.boot</groupId>
              			<artifactId>spring-boot-starter-security</artifactId>
              		</dependency>
              		<dependency>
              			<groupId>org.springframework.boot</groupId>
              			<artifactId>spring-boot-starter-thymeleaf</artifactId>
              		</dependency>
              		<dependency>
              			<groupId>org.springframework.boot</groupId>
              			<artifactId>spring-boot-starter-web</artifactId>
              		</dependency>
              		<dependency>
              			<groupId>org.thymeleaf.extras</groupId>
              			<!-- spring-boot-starter-parent, v3.2.2, no thymeleaf-extras-springsecurity5 -->
              			<!-- <artifactId>thymeleaf-extras-springsecurity6</artifactId> -->
              			<artifactId>thymeleaf-extras-springsecurity5</artifactId>
              		</dependency>
              
              		<dependency>
              			<groupId>org.springframework.boot</groupId>
              			<artifactId>spring-boot-starter-tomcat</artifactId>
              			<scope>provided</scope>
              		</dependency>
              		<dependency>
              			<groupId>org.springframework.boot</groupId>
              			<artifactId>spring-boot-starter-test</artifactId>
              			<scope>test</scope>
              		</dependency>
              		<dependency>
              			<groupId>org.springframework.security</groupId>
              			<artifactId>spring-security-test</artifactId>
              			<scope>test</scope>
              		</dependency>
              		<!-- Database Driver - MySQL -->
              		<dependency>
                          <groupId>mysql</groupId>
                          <artifactId>mysql-connector-java</artifactId>
                          <version>8.0.26</version>
                      </dependency>
                      <!-- Hibernate Entity Manager -->
                      <dependency>
                          <groupId>org.hibernate</groupId>
                          <artifactId>hibernate-core</artifactId>
                      </dependency>
                      <!-- Spring Boot Starter for Data JPA -->
                      <dependency>
                          <groupId>org.springframework.boot</groupId>
                          <artifactId>spring-boot-starter-data-jpa</artifactId>
                      </dependency>
              	</dependencies>
              
              	<build>
              		<plugins>
              			<plugin>
              				<groupId>org.springframework.boot</groupId>
              				<artifactId>spring-boot-maven-plugin</artifactId>
              			</plugin>
              		</plugins>
              	</build>
              
              </project>

  > Spring Security Filter
  - Architecture
  - Hyper link:
    https://docs.spring.io/spring-security/reference/servlet/architecture.html

