<style>@import url("//readme.codeadam.ca/readme.css");</style>

## Requirements: Lego City GPS: Version #1

### Student Names

Ellis Chang (N01591227)  
Bassil Younes (N01572641)

### Project Name (and version)

Lego City GPS v1   

### Technology Stack

- Python  
- Frontend  
    - REACT  
- Backend  
    - Node
    - SQL for the database

### Project Purpose

The BrickMMO GPS is a web-based application that allows users to track the locations of LEGO cars in a virtual city. The application will be useful for LEGO enthusiasts, gamers, and anyone who wants to explore a digital city in real-time. The application will include features like live tracking of cars' movements on a 2D map and the ability to view past locations of each car. The application will work by collecting data from the cars' movements and storing them in a database. Users can access the data through a deployed website, which will show the cars' current location in real-time and allow them to view past locations of each car. The application will be built using Python for the tracking functionality, REACT for the frontend, Node for the backend, and SQL for the database.

### Features List

**Must Haves**
- Track the x-y coordinates of each car on a 2D grid map
    - Automatically perform this process repeatedly after a set interval of time
- Insert each car coordinate into a database after each tracking evcent
- Allow for viewing live data of car locations on a deployed website
- Allow for viewing of past car locations
    - Slider bar to show location history of a vehicle

**Should Haves**  

**Nice to Haves**  
- Traffic Jams: detect when many cars are in the same vicinity
    - Create a red zone on the map in these areas

### Narrative Description

**Viewing the live map of multiple cars (non-admin users)**  
- User will search and open the GPS brickmmo website [(gps.brickmmo.com)](https://gps.brickmmo.com/)  
    - The frontend will be deployed using this domain
- User will see a digital 2d map of the Lego city with up to 7 cars on it
    - This frontend will be built with REACT
- The user will see the cars move in real time
    - Data will be retrieved from an SQL database using Node and outputted onto the REACT frontend

**Viewing the history of car locations (non-admin users)**
- User will click on one of the cars that is displayed on the map  
    - They will be taken to another screen showing the same map with only the selected car visible
- The user will use a slider to see the past locations that the car has been in the city
    - The locations will be retrieved from historical data saved in
the SQL database

**Admin Access Features**
- Add cars to the city GPS application
- Delete cars from the city GPS application

### User Stories
- A user will visit the Brickmmo GPS website
- They will be able to see the virtual map of the Lego city with the current car locations automatically updating in real time
- They will slide the history slider bar to go back in time and see the past car locations

### Database Description

See Excel Document with Tables

### Dataflow Diagrams

![Figure 1](../images/v1-requirements-fig1.png)  
![Figure 2](../images/v1-requirements-fig2.png)

### Wireframes

![Frontend User Wireframe](../images/v1-requirements-user-frontend-wireframe.png)  
![Frontend User Login Wireframe](../images/v1-requirements-user-login-frontend-wireframe.png)  
![Frontend Admin Wireframe](../images/v1-requirements-admin-frontend-wireframe.png)

### Project Timeline

[&#10132; Back to Version 1](../gps-about/v1)

---

<a href="https://brickmmo.com">
<img src="https://brickmmo.com/images/brickmmo-logo-horizontal.jpg" width="100">
</a>