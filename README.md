# Scala and sbt for Docker
## Supported tags
* `1.3.4`, `latest` [(Dockerfile)](https://github.com/versates/docker-sbt/blob/1.3.4/Dockerfile)
* `1.3.4-jdk`, `jdk` [(jdk/Dockerfile)](https://github.com/versates/docker-sbt/blob/1.3.4/jdk/Dockerfile)

[![](https://images.microbadger.com/badges/image/versates/sbt.svg)](https://microbadger.com/images/versates/sbt "Get your own image badge on microbadger.com")

## Base image
* [openjdk](https://hub.docker.com/_/openjdk) (JRE 11 | JDK 11 / Debian Buster Slim)

## JRE Only
Default versions are intended to run [Scala](http://www.scala-lang.org) and [sbt](http://www.scala-sbt.org) applications. If you want to compile and build Scala applications, use the JDK version instead.

## JDK Version
JDK is built with the required dependencies for building and packaging Scala and Java applications with sbt.

## License
This code is open source software licensed under the [Apache 2.0 License]("http://www.apache.org/licenses/LICENSE-2.0.html").
