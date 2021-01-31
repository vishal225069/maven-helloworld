Hello World! (WAR-style)
===============

This is the simplest possible Java webapp for testing servlet container deployments.  It should work on any container and requires no other dependencies or configuration.

```
git clone https://github.com/submah/maven-helloworld.git

docker run -it --rm --name my-maven-project -v /root/maven-helloworld:/usr/src/app  maven   mvn -f /usr/src/app clean package

```
