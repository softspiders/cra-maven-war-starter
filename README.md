# cra-maven-war

An example of building a war of create-react-app on Maven

## Requirements

* [JDK](https://java.com/ru/download/) >= 1.5
* [*Maven*](https://maven.apache.org/)
* [*Node*](https://nodejs.org/en/download/package-manager/)
* [*create-react-app*](https://facebook.github.io/create-react-app/)
* [*Tomcat*](http://tomcat.apache.org/) or another servlet container - for running

## Build

```sh
mvn package
```


## Deploy

The resulting war is in the *target* directory
Copy the war to *webapps* directory of some running Tomcat server

## Run
Go to the [cra-maven-war](http://localhost:8080/cra-maven-war) from the browser

## Authors

[Alexander Lapygin](https://github.com/AlexanderLapygin)

## Inspired by

[Deploy React Applications in a Servlet Environment](https://www.megadix.it/blog/create-react-app-servlet/)

### License

Licensed under the [MIT license](./LICENSE). 

