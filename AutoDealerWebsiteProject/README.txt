Graduate project: Develop a Digital Automobile Website Platform

Description :
1. Digital Automobile website platform consists of multiple dealers
2. Each dealer can have multiple brands of automobiles like Tesla, Audi, Mercedes Benz, accord, etc
3. Customer uses this user interface to browse the dealer frame with or without an account
4. Customer can send queries to the selected dealer

Projects were divided into 4 modules and each module consists of 4 teams

Module 1
	Develop a User Interface for consumers to browse the Dealer Frame (contains home page, vehicle search results, vehicle details and a form to contact a dealer)

Module 2
	Manage Inventory and display the inventory on the vehicle search results page and vehicle details page

Module 3
	Manage Incentives and attach the incentives to every vehicle that is displayed on the vehicle details page

Module 4
	Define a user interface for submitting, response forms to dealers and have a mechanism for dealer to track all the leads in a user interface

I was part of Module 4, team 3

1. I Designed and developed Submit Response form UI with an auto-filled customer and car information using java swing for dealers to respond to the customer queries ( refer SubmitResponse.java)
2. The system sends response by email( used HTML template) (refer SendEmail.java, emailTemplate.html, temp.html, SampleEmailImage.png)
3. The responses are stored and displayed in registered customer's history page with the customer's has an account 

Excepted Result :

1. Once dealer clicks respond button after selecting particular customer query after going through their deals list, 
Submit Response form UI opens with all the customer and car information auto-filled

2. Auto filled information is getting from SQL database using that particular deal ID ( used JDBC API)

3. After going through the query, Dealer type their response in the response text area and clicks submit button

4. Once Dealer clicks submit button, the response goes through the email, as well as the customer can see the response in the system history page if the customer has an account with the system 

Instructions to build:

1. can run through any IDE like Eclipse,IntelliJ, visual studio

2. copy reference libraries jar files - activation.jar, dom4j-2.1.1.jar, javax.mail.jar, smtp-1.6.2.jar, sqljdbc.jar

3. need a database to store customer, car inventories

4. once user runs lead.java(team2 work) file, submit response form UI opens

5. Then dealers write their comments in the response text area and click submit button

6. check the email by logging into an account( refer attached SampleEmailImage.png )


Im also particpating in SITAC IT Architecture Competition 2020

Project Name : Self-guided learner/Learning Assistance System

1. As a part of Deliverable 1,Defined and documented scope, key features, related business processes, system context diagram, flow diagram, epics, user stories, and risks
2. As a part of Deliverable 2,designed and documented Business Process, UX/UI and Data Architecture

It's an ongoing project, yet to deliver deliverable 3( on Feb end) and deliverable 4(on march end)
Please refer attached deliverable 1 and deliverable 2 document

Please refer my Github link to refer all of my graduate assignments
https://github.com/sahanadarsh




