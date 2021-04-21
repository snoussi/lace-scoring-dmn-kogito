# CDS Demo - LACE Score DMN on Kogito Decision Service

DMN implementation of LACE scocre.
The LACE score identifies patients that are at risk for readmission or death within 30 days of discharge.
This demo Demonstrates DMN on Kogito capabilities, including REST interface code generation.

## Installing and Running

### Prerequisites

You will need:

- Java 11+ installed
- Environment variable JAVA_HOME set accordingly
- Maven 3.6.2+ installed

### Run in Local Dev Mode

```
mvn clean quarkus:dev
```

## OpenAPI (Swagger) documentation

You can visualize and interact with the generated specification using the embbeded [Swagger UI](http://localhost:9090/swagger-ui) or importing the generated specification file on [Swagger Editor](https://editor.swagger.io).

In addition client application can be easily generated from the swagger definition to interact with this service.
