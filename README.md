README

This project is a Java-based web application that retrieves and processes data from the Korea Racing Authority (KRA) website. The application is built using the Spring Boot framework and uses various libraries such as Jsoup and Apache POI.

Getting Started
To get started with this project, you will need to have the following installed on your machine:

JDK 1.8 or later
Maven 3.0 or later
To build and run the application, follow these steps:

Clone the repository to your local machine.
Open a terminal or command prompt and navigate to the root directory of the project.
Run mvn spring-boot:run to build and start the application.
Once the application is running, you can access the endpoints using a web browser or a REST client such as Postman.
Endpoints
The application provides the following endpoints:

GET /horseList
Retrieves a list of horses belonging to a particular trainer and their medical history. The endpoint accepts a query parameter jo, which is the name of the trainer.

Example usage:

perl
http://localhost:8080/horseList?jo=22조
GET /trainers
Retrieves the trainer number for a given trainer name. The endpoint accepts a query parameter trainerName, which is the name of the trainer.

Example usage:

bash
http://localhost:8080/horses
Request body:

json
Copy code
{
    "trNo": "TRA201611"
}
Libraries Used
The following libraries were used in this project:

Spring Boot: A popular framework for building web applications in Java.
Jsoup: A Java library for parsing HTML documents.
Apache POI: A Java library for working with Microsoft Office documents.


