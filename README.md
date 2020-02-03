# TodoList

## Resume

* Provide an authentication feauture.
* a todo crud

## Built With

* 	[Maven](https://maven.apache.org/) - Dependency Management
* 	[JDK](http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html) - Java™ Platform, Standard Edition Development Kit 
* 	[Spring Boot](https://spring.io/projects/spring-boot) - Framework to ease the bootstrapping and development of new Spring Applications
* 	[MySQL](https://www.mysql.com/) - Open-Source Relational Database Management System
* 	[git](https://git-scm.com/) - Free and Open-Source distributed version control system 




## Running the application locally

There are several ways to run a Spring Boot application on your local machine. One way is to execute the `main` method in the `com.arc.sbtest.SBtemplateApplication` class from your IDE.

- Download the zip or clone the Git repository.
- Unzip the zip file (if you downloaded one)
- Open Command Prompt and Change directory (cd) to folder containing pom.xml
- Open Eclipse 
   - File -> Import -> Existing Maven Project -> Navigate to the folder where you unzipped the zip
   - Select the project
- Choose the Spring Boot Application file (search for @SpringBootApplication)
- Right Click on the file and Run as Java Application

Alternatively you can use the [Spring Boot Maven plugin](https://docs.spring.io/spring-boot/docs/current/reference/html/build-tool-plugins-maven-plugin.html) like so:

```shell
mvn spring-boot:run
```





### URLs

|  URL |  Method | Remarks |
|----------|--------------|--------------|
|`http://localhost:8080/list-todos`         | GET | Selectionner tous les TODOS|
|`http://localhost:8080/add-todos`                  | POST | Ajouter un TODO|
|`http://localhost:8080/delete-todos`                           | DELETE | Supprimer un TODO |
|`http://localhost:8080/update-todos`                     | POST | Modifier un TODO|


  
## Resources

* [in 28 Minutes ](https://courses.in28minutes.com/)


