<center>
<h1> Doctor Appointment App</h1>
</center>
<center>
<a href="Java url">
    <img alt="Java" src="https://img.shields.io/badge/Java->=8-darkblue.svg" />
</a>
<a href="Maven url" >
    <img alt="Maven" src="https://img.shields.io/badge/maven-3.0.5-brightgreen.svg" />
</a>
</center>
This project is a Doctor App project built using Spring Boot with Java.

---

## Framework Used
* Spring Boot

---

## Language Used
* Java

---

## Data Model

The All ...ModelClass  is defined inside the model packages which has the following attributes:
   
  

## Data Flow

1. The user sends a request to the application through the API endpoints.
2. The API receives the request and sends it to the appropriate controller method.
3. The controller method makes a call to the method in service class.

4. The method in service class builds logic and retrieves or modifies data from the database, which is in turn given to controller class
5. The controller method returns a response to the API.
6. The API sends the response back to the user.

---

## Functions used :-

### API Endpoints :-
</br>
<b> add </b>

* PostMapping:

This endpoint makes a call to method in Service class which is connected to database. In database we add a new given through API.


* GetMapping: 

This endpoint returns all data through API.


* PutMapping: 

This endpoint makes a call to method in Service class which is connected to database. In database we update.


* DeleteMapping: 

This endpoint makes a call to method in Service class which is connected to database. In database we delete through API.

---

---

## 📝Project Summary

I have created Doctor App project using data source project.  In this project, In this project user  Can delete , update , get ,  can find. etc...

