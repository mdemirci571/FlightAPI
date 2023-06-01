# FlightAPI

Project
You’ll build a Flight Reservation API with 
Django Rest Framework that allows users to

● register/login/logout <br/>
● crud operations for flights <br/>
● crud operations for reservation <br/>


# Actor Profiles Specification
This section describes all the Actors and their profiles within the scope of the Business
Requirements being documented. An Actor is a person, organization, or an external
system/sub-system/program that has interactions with the Application. Actors, by definition, are
external to the system with which they are having interactions. Actors have goals that are
achieved by use cases. Typically, Actors have behavior and are represented by the roles they
play in the use cases. An Actor stimulates the system by providing input and/or receiving
something of measurable value from the system. <br/>

The scope of the application will be determined based on the following actors;

Actor:   Description
Client:  Clients should be internet literate, authenticated. Clients can be any
individual using the web interface or any system or application using
the programmatic access to the API.

Admin: Internet literate, authenticated. Admin is the representative from the
vendor

Actors will have the following roles;
● Client:
○ API Client

● Admin:
○ API Admin

# Scenarios Specification

The scope of the application will be determined based on the following scenarios;
● Search FRA: Clients can search..
● View information: Clients can see flight details.
● Display results: Clients can see the flight output from the web or API.
● Authentication and authorization: Clients must be authenticated and authorized.


# In Scope

● Search Flight:
○ All actors
● View Flight and Reservation information:
○ All actors
● Display results:
○ All actors
● Authentication and authorization:
○ Client
○ Admin
