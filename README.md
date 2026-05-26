# First REST API Spring (Task 2)

This is a REST API application for managing products, built with Java and Spring Boot. 
It uses an H2 in-memory database to store data and Swagger UI for API documentation and testing.

## Technologies Used
* Java 21 (or your version)
* Spring Boot
* Spring Data JPA
* H2 Database
* Springdoc OpenAPI (Swagger UI)

## How to run the application
1. Clone the repository.
2. Run the application using your IDE (execute `FirstRestApiSpringApplication.java`).
3. The server will start on port `8080`.

## Endpoints / How to test
You can test the application using Swagger UI: `http://localhost:8080/swagger-ui/index.html`

### 1. Create a Product (POST)
<img width="968" height="887" alt="image" src="https://github.com/user-attachments/assets/779b90dc-ad77-489b-8d4e-d6073246615c" />


### 2. Get All Products (GET)
<img width="959" height="899" alt="image" src="https://github.com/user-attachments/assets/a11639cd-5ed3-43f0-90ec-3a2b0ac0f980" />

### 3. Update a Product (PUT)
<img width="1204" height="905" alt="image" src="https://github.com/user-attachments/assets/534fc18c-48b0-45b0-b045-43da7db38205" />


### 4. Delete a Product (DELETE)
<img width="975" height="813" alt="image" src="https://github.com/user-attachments/assets/22c837ee-83da-4efb-9064-a2510610ea57" />


## Database Access
The application uses an H2 in-memory database. You can access the console at: `http://localhost:8080/console`
* **JDBC URL:** `jdbc:h2:mem:testdb`
* **User Name:** SA
* **Password:** *(leave blank)*

<img width="649" height="505" alt="image" src="https://github.com/user-attachments/assets/f431f20a-ef60-4920-a2bb-d4e6279526e9" />

<img width="950" height="574" alt="image" src="https://github.com/user-attachments/assets/95eba461-26f3-475a-b7df-33d2877da00b" />

<img width="992" height="455" alt="image" src="https://github.com/user-attachments/assets/13dc9076-de80-45fb-892c-6ebfefeeb905" />
I added new post to show that DB is workibg
