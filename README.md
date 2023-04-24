# URL Hit Counter

## Framework Used
* Spring Boot
## Language Used
* Java
## Data Flow

In this project, we have two layers-

* Controller - The controller layer handles the HTTP requests, translates the JSON parameter to object, and authenticates the request and transfer it to the business (service) layer. In short, it consists of views i.e., frontend part.
* Service -The business layer handles all the business logic. It consists of service classes and uses services provided by data access layers.


# Data Structure Used

* HashMap

# Summary

In this project , when visitor go to the url it increses it's hit count by 1. So we find the username and hit count of visitor comes to URL. 
