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
