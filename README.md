# spring-boot-kotlin-web-boilerplate
For the bare minimum needed to build web applications with Spring Boot and Kotlin

## To run
First, check that all the required dependencies have been installed.

Then, go to the root of the repository and then do the following at the terminal

```bash
./gradlew bootRun
```

After a few seconds the web content should be served and visible via the localhost at port `8080` at http://localhost:8080/.

If you are on a machine running on a Mac / MacBook, press `Control` + `C` to termination the session. 

## Building from Spring Initializr
Go to https://start.spring.io/ and choose the desired config. For the config used in this work, click [here](https://start.spring.io/#!type=gradle-project&language=kotlin&platformVersion=2.4.5.RELEASE&packaging=jar&jvmVersion=11&groupId=com.example&artifactId=demo&name=demo&description=Demo%20project%20for%20Spring%20Boot&packageName=com.example.demo&dependencies=web,mustache,data-jpa,h2,devtools). 

## Reference
1. Building web applications with Spring Boot and Kotlin at https://spring.io/guides/tutorials/spring-boot-kotlin/
