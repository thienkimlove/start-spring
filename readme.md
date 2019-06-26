## Start Spring Boot 

### Install

* `mvn clean && mvn package`

* Run with `java -jar target\startproject-1.0-SNAPSHOT.jar`

* `$ curl localhost:8080`
Greetings from Spring Boot!

* Or run with `mvn clean spring-boot:run`

### IDE Note

If you pick up IntelliJ IDEA as your IDE for this tutorial, you have to install `lombok` plugin. 
 
After this you have to ensure that `"Enable annotation processing"` 

checkbox is ticked under: `Preferences → Compiler → Annotation Processors`, as it is described.

### Find Component Maven for Spring Boot

`https://github.com/spring-projects/spring-boot/tree/master/spring-boot-project/spring-boot-starters`

Access to `pom.xml` for each project to find needed packages.

Or using `Spring Initializr` in IDE by `New Project > Spring Initializr > Type the needed package`


