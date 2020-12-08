  # **EarthBnB - Server (Rental Site Clone)**

This is the server side of our EarthBnB project created by Talent Path's 'Quaran-Team' of full stack developers located in Atlanta, GA and Houston, TX.

The goal of this project was to practice weekly agile sprints by creating an e-commerce product page(s) for 20 items in a very similar theme to that of the commonly known retail site Amazon. Each team member made contributions to the client, server, and database of the project in order to understand how a full stack application functions.

The client repository can be found here _-_ GitHub Repo = https://github.com/NeelyAnne/client-EarthBnB .

We created the server utilizes Java Spring Boot for bean creation, Maven for our dependencies, and FlyWay to manage our database migrations. 

The server is not currently deployed anywhere but can be cloned and run in our preferred IDE, IntelliJ. This will also require MySQL to function.

---

To run it locally:

Note: You must have installed Java (version 8 or higher), Maven (can be used as mvn or mvnw), and MySQL and MySQL Workbench

(1.) Clone the repository

(2.) Open the project and make sure to cd into the folder named API within the repository (This can be within your command line interface or within IntelliJ.)

(3.) Open Workbench and under the username and password 'root', create a database called 'earthdb'. This will allow for storage of information found in your sql migration files in the server repository.

(4.) Back in the command line or IntelliJ, run the command 'mvn(w) spring-boot:start'

 - If you make updates to the sql seed files, a 'mvn(w) clean' and 'mvn(w) flyway:clean' should be preformed before the server is started to ensure there is not conflict of migrations.

 - If you get an error command not found MVN you will need to download and install it locally which can be done here: https://maven.apache.org/download.cgi

(5.) To see the raw Json while the server is running visit "http://localhost:8080/all/products/" or "http://localhost:8080/1"

![alt text](https://github.com/NeelyAnne/client-EarthBnB/blob/master/landing.png "Landing Page")

---

**The Quaran-Team! consists of:**

- Bilikis Orulebaja
  - https://github.com/borulebaja
- Brandt Campbell
  - https://github.com/Reboot82
- Brian Loveless
  - https://github.com/BrianLoveGa
- Juan Avalo-Santiago
  - https://github.com/avalojc
- Michal Terranova
  - https://github.com/mrterranova
- Neely Mann
  - https://github.com/NeelyAnne
- Trevor Taylor
  - https://github.com/Trevis42

**Led by management team:**

Fred Zirdung and Jothi Nedungadi

## **Languages/Technologies:**

- Java
- Spring-Boot
- Maven
- Fly Way
- MySQL
- MySQL Workbench
- Lombok
- Apache
- Velocity

---

All rights reserved by Talent Path 2020
a division of Genuent.

https://talentpath.com/what-we-do/

https://genuent.com/
