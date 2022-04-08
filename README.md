# Ubuntu images with jdk18 ready to work

With this image you can run your JAVA applications using jdk18. It is built used tag version of Ubuntu.

## Quick reference

With thiw image, you can use commands like this:

```Docker
FROM diegolaucsen/ubuntu-jdk18:20.04

COPY target/*.war /app.war

ENTRYPOINT ["java","-jar","/app.war"]
```

## Available Tags

* [20.04](https://github.com/Laucsen/ubuntu-jdk18/tree/master/20.04)

## Read more

* [Ubuntu](https://hub.docker.com/_/ubuntu)
