## POSTiT - place for all your thoughts (An attempt to make a reddit)

## 1. What it is??

This is an attempt to use my knowledge of frontend and backend to do a full-stack web-development project.
This project tries to mimic a travel and accommodation booking website like airbnb.

### Goal of doing this project:
The aim main behind trying to do this project was to work with a backend that has a complicated 
entity relationship. The complexity of the underlying entity relationships can be understood from the
project UML diagram add to in the root of this repository.

This project aims to implement many of the features that airbnb or any other accommodation booking website has.
It provides the following feature:
 
1. Hosting agents can host their properties.
2. Users can book/cancel accommodation bookings.
3. Users can check their past travels and also upcoming bookings.
$. Users can add comment/feedback for the accommodation they have booked.

## 2. TECH STACK

Frontend: React and Redux

Backend: Java Spring.

Database: AWS RDS
 
## 3. WEBAPP STRATEGY

Our general architecture is the following:

**3.1.  Frontend react client**

The frontend is developed using react and redux.

**3.2.  Services**

The services will handle interaction between client and database.
The backend is implement using Java spring. 

**3.3. Database** 

The databases will store information about users, hosting agents, properties hosted and comments/feedback
received from users. A database relation will record property/hotel and its corresponding comments.
The database used is a relational database for storing the user data.

# 4. Important entity relations mapped in the backend

* One-Many relationship between hosting agent and property.
* One-Many relationship between property/hotel and comments.
* Many-many relationship between user and bookings. 
* One-one relationship between booking and payment details.
* One-Many relationship between property/hotel and image urls
* One-many relationship between property/hotel and different availability dates.
