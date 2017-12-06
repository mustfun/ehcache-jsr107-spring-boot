# ehcache-jsr107-spring-boot

update from 
https://github.com/gibsong/ehcache-jsr107-spring.git

update info :
- update ehcache to 3.4.0
- update spring boot
- update run port to 8090
- more 

Building the application:
-This application can be built using maven 3.2 or above.  Make sure you are in the project root directory "ehcache3-jsr107-spring", or if you renamed it then it's the directory with the pom.xml file.  Now from the command line type:
mvn clean install

Running the application:
-Once again use maven to run this application, and you must be in the project root directory. From the command line type:
mvn spring-boot:run

What is the application url?
-The url template is http://localhost:8090/person/{ssn} where {ssn} should be replaced by an actual number, like the following:
http://localhost:8090/person/987654321


