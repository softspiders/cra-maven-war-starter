# *cra-maven-war*

An example of building a war of create-react-app on Maven

## Direct feature descendants

[cra-maven-war](https://github.com/softspider/cra-maven-war)

## Requirements

* [*create-react-app*](https://facebook.github.io/create-react-app/)
* [*JDK*](https://java.com/ru/download/) >= 1.5
* [*Maven*](https://maven.apache.org/)
* [*Node*](https://nodejs.org/en/download/package-manager/)
* [*Tomcat*](http://tomcat.apache.org/) or another servlet container - for running
* [*TypeScript*](https://www.typescriptlang.org/)

## Build

```sh
mvn package
```


## Hot deployment

[Start Tomcat server](https://www.webucator.com/how-to/how-start-stop-apache-tomcat-from-the-command-line-windows.cfm).
  
Now the resulting *cra-maven-war.war* is in the *target* directory.
  
Copy the *cra-maven-war.war* to the *webapps* directory of the Tomcat server.

Wait a few seconds for deployment.

## Run

Run [http://localhost:8080/cra-maven-war](http://localhost:8080/cra-maven-war) from the browser

## Run from another path

Rename *cra-maven-war* for example to *cra-maven-war-another-path*.  
Deploy it to the *Tomcat*.  
Run [http://localhost:8080/cra-maven-war-another-path](http://localhost:8080/cra-maven-war-another-path) from the browser



## Authors

[Alexander Lapygin](https://github.com/AlexanderLapygin)

## Inspired by

[Deploy React Applications in a Servlet Environment](https://www.megadix.it/blog/create-react-app-servlet/) by
[Dimitri De Franciscis (megadix)](https://github.com/megadix)

### License

Licensed under the [MIT license](./LICENSE). 

