
# Sporty_Shoe
 Shoe Shop Inventory Site - CRUD functionality, User authentication, Role Based Access :
- Agile Scrum Development Cycle
- Eclipse EE
-	Maven
-	Java 1.8
- SpringBoot
-	Thymeleaf
-	CSS & Bootstrap
-	MySQL



# Test the Application
1. Download project, Inport as Maven project (Eclipse)

2. Run the Spring Boot application: ShoeShopAdminApplication.java

3. Open a web browser for the app: http://localhost:2023

4. Log in using one of the accounts (These are all configurable in the "SecurityConfig.java" file.)


| user id       | password      |   roles               |
| ------------- |:-------------:| ---------------------:|
| Keshav        | Keshu@10      | "MANAGER", "ADMIN"    |
| Ashu          | ASH@123       | "EMPLOYEE"            |
| Vini          | Vini@123      | "EMPLOYEE", "MANAGER" |
| Tanya         | test123       | "EMPLOYEE", "ADMIN"   |

5. Confirm that you can login and access data based on the roles.


# Prebuild  
Created a workflow using the Scrum methodology: This workflow was spread out of 3 sprints, with a duration of one long sprint (2 weeks) followed by two short springs(1 week). (4 weeks total dev cycle)
This is captured in "img: 1.1"

"img: 1.1" Click on images to see more clearly. 

<img width="490" alt="SprintPlanning" src="https://github.com/Keshav-LB/Sporty_Shoe/assets/65038133/f2f1878f-f9b6-4893-8414-9f62dc2fc4e0">


# Build
## Sprint 1 (week 1 - 2) Backend Focus
### Project Set Up 
 - Created a visual diagram with the files, class’s & method's that I intended to use in the project. (Check Img 1.2)

 - Create MySQL Database (IMG 1.3) Files to create Database in MySQL are above in repository (Schema: shoe_shop_inventory)

   
![1](https://github.com/Keshav-LB/Sporty_Shoe/assets/65038133/9a0b462b-090f-45c0-a193-83ca35768dd2)

![2](https://github.com/Keshav-LB/Sporty_Shoe/assets/65038133/50ce0d18-e375-4e07-af0c-95b5a2020603)

- Create Project structure and add dependencies using SpringInitalizr https://start.spring.io/

![3](https://github.com/Keshav-LB/Sporty_Shoe/assets/65038133/eb8f2c0d-c8f9-4bb5-b455-245349f87333)

### Packages (Java files & Interfaces) ###

1.  com.shoeshop.admin.application (Main java class to start application)
       -  ShoeShopAdminApplication.java
        
2.	com.shoeshop.admin.application.config (Security Config, Store passwords and assign user restrictions) 
       -	SecurityConfig.java
3.	com.shoeshop.admin.application.controller (processing incoming requests) 
       -	LoginController.java
       -  ShoeController.java

4.	com.shoeshop.admin.application.dao (logic required to access data sources)
       -	ShoeRepository.java 
       
5.	com.shoeshop.admin.application.entity (representing data that can be persisted to the database)
       -	Shoe.java 
       
6.	com.shoeshop.admin.application.service  (Bussiness logic and CRUD functionality) 
       -	ShoeService.java 
       -  ShoeService.lmpl.java

         




IMG 1.2 Click on images to see more clearly. 


![4](https://github.com/Keshav-LB/Sporty_Shoe/assets/65038133/f73c955a-9c23-4fb3-808d-e1a4a5c05a77)


## Sprint 2 (Week 3) Front-end Focus


      
-	Create Administration login.

- Create shoe inventory page.
 
-	Create shoe add page.

- Style pages.
  



## Sprint 3 (Week 4) Testing With Users

- User Test
- Fixes Bugs


