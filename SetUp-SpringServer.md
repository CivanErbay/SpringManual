## Setup Spring Server - (ToDo App Backend)

###Architecture of the Backend
### Set up several backend layers 
#### Create Classes for that (for example..)


I. Controller (highest layer with Rest-Controller)  
II. Service   
III. Database  
IV. Models - several, single Items or enums

# Step 1:
1. Set up packages and empty classes 
![picture alt](packages.png)

# Step 2:
### Controller

Controller is the interface (Schnittstelle) between our back- and frontend.
First its necessary to initialize it.
![picture alt](Controller1.png)

### Main Model

Initialize your Task class, from which you create the core instances for your later program.   
Dont forget to set @Data (for all the getters, setters & toString method) and @AllArgsConstructor aswell as the @NoArgsConstructor.  
![picture alt](Task.png)


### Database 

Set up your Database with an empty Arraylist of Tasks, which will store all the instances of Tasks.  
Dont forget to set @Data and @Repository(to provide dependency Injection for the Service class)
You create all the methods which logic right here aswell. 
![picture alt](Database.png)







