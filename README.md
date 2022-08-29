# scala-web-bloop-sbt-spring-actuator-simple

## Description
A POC for actuator in springframework.

Compiled and ran from build server `bloop`.

# Build note
Dependencies must be compatable with jdk8 or less.

## Tech stack
- bloop
- scala
- bloop-sbt

## Docker stack
- eed3si9n/sbt

## To run
`sudo ./install.sh -u`
Available at:
- http://localhost
- http://localhost/health
- http://localhost/info

## To stop (optional)
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credits
- https://www.javatpoint.com/spring-boot-actuator
