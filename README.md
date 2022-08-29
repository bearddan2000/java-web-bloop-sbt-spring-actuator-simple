# java-web-bloop-sbt-spring-actuator-simple

## Description
A POC for actuator in springframework.

Compiled and ran from build server `bloop`.

# Build note
Dependencies must be compatable with jdk8 or less.

## Tech stack
- bloop
- java
- bloop-sbt

## Docker stack
- openjdk:8-jdk-alpine

## To run
`sudo ./install.sh -u`
Available at:
- http://localhost/actuator
- http://localhost/hello
- http://localhost/actuator/info

## To stop (optional)
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credits
- https://www.javatpoint.com/spring-boot-actuator
