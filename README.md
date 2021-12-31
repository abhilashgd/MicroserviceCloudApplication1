# MicroserviceCloudApplication1

//to install maven using homebrew
% brew install maven

//creating maven project link
https://maven.apache.org/guides/getting-started/maven-in-five-minutes.html

//creating a project
mvn archetype:generate -DgroupId=com.microservice.app -DartifactId=microservicetest -DarchetypeArtifactId=maven-archetype-quickstart -DarchetypeVersion=1.4 -DinteractiveMode=false

//to check structure of project in terminal
% tree
// % brew install tree // to install tree 

//creating spring boot banners
https://devops.datenkollektiv.de/banner.txt/index.html
//banner for customer
                          ,--.
,---. ,--.,--.  ,---.  ,-'  '-.  ,---.  ,--,--,--.  ,---.  ,--.--.
| .--' |  ||  | (  .-'  '-.  .-' | .-. | |        | | .-. : |  .--'
\ `--. '  ''  ' .-'  `)   |  |   ' '-' ' |  |  |  | \   --. |  |
`---'  `----'  `----'    `--'    `---'  `--`--`--'  `----' `--'

//command to run docker-compose.yml
% docker compose up -d
//Command to list docker compose containers running
% docker compose ps
//access pgadmin
http://localhost:5050
create a database with name customer

//postman testing
URL: localhost:8080/api/v1/customers
Body: RAW-JSON:
{
"firstName": "abhilash",
"lastName": "gd",
"email": "abhilashgd@test.com"
}

//inside pdadmin->customer database-> select customer table, query ->select * from customers;
