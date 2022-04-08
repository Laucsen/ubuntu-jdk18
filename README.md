# Ubuntu images with jdk18 ready to work

With this image you can run your JAVA applications using jdk18

You can use commands like this:

```Docker
FROM ubuntu-20.04-jdk18

COPY target/*.war /app.war

ENTRYPOINT ["java","-jar","/app.war"]
```
