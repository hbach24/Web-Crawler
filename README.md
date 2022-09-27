# Web Crawler - CS172 Project
## Prerequisites: 
- Have Java JDK 1.7 or above installed (https://www.oracle.com/java/technologies/downloads/)
- Have Maven installed (https://maven.apache.org/download.cgi)

## How to Deploy the System 
For Windows
#### Deploying backend:
1. Use the indexer.bat to execute on the terminal to index and search for the query word. Arguments in the .bat file can be edited to get specific searches.
2. Use mvn spring-boot:run to start the spring application
3. Navigate to http://localhost:8080/api/articles?query=
#### Deploying frontend:
1. Ensure that the spring application is running.
2. Navigate to the index.html file and run open ./index.html


Search Engine Example Demo
![image](https://user-images.githubusercontent.com/57569284/192456439-9e8f6190-7bc9-4b68-b735-ed16fedb130a.png)

