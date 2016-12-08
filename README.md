# Atlassian Confluence in Docker

There is an offical [Docker Image](https://hub.docker.com/r/cptactionhank/atlassian-confluence/) which is based on OpenJDK:8. But as a matter of fact, atlassian only supports the Oracle Java.

So, this build is been updated to make of for the java problem and is currently using 'Confluence:6.0.1' as its base.

You probobly need to build the [Oracle Java:8](https://github.com/subugoe/oracle-java_docker) first.

It is a pretty streight forward build, as usuall:
```
 $ docker build --tag=confluence:6.0.1 --force-rm --no-cache .
```
