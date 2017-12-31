## Configurar Postgres
En el archivo `/src/main/java/ca/uhn/fhir/jpa/demo/FhirServerConfig.java` modificar lineas 53-55

## Running hapi-fhir-jpaserver-example 

En EC2 hay que correr esto primero:
```
 export JAVA_TOOL_OPTIONS="-Xmx512m -Xms256m"
```
Instalar:
```
mvn clean install
```
Iniciar:
```
mvn jetty:run
```
