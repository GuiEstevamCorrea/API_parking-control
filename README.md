# API Parking Control

The API Parking Control is a project developed to manage apartment parking garage operations. This API provides CRUD (Create, Read, Update, Delete) functionality to effectively handle information related to parked vehicles, apartments, and owners. The project is built using technologies such as Postgres, Java Spring, and Docker, offering a comprehensive solution with scalability in mind.

## Features

- **Vehicle Management**: Perform operations to add, retrieve, update, and delete information about vehicles parked in the garage.

- **Apartment Management**: Register, query, update, and remove data associated with apartments.

- **Owner Management**: Maintain a database of apartment owners, allowing operations for creation, retrieval, updating, and deletion.

## Technologies Used

- **Postgres**: Utilized as a reliable relational database to store data about vehicles, apartments, and owners.

- **Java Spring**: Employed to build the API efficiently and robustly, enabling the implementation of CRUD operations.

- **JUnit**: Used for unit testing to ensure code quality and integrity, aiding in the early detection of issues.

- **Docker**: Implemented to provide containerization, ensuring consistency across different environments, such as development, testing, and production.


## Getting Started

1. Clone this repository to your local machine:

    ```bash
    git clone https://github.com/GuiEstevamCorrea/API_parking-control.git
    ```

2. Navigate to the project directory:

    ```bash
    cd API_parking-control
    ```

3. Run the Docker container for the Postgres database:

    ```bash
    docker-compose up -d
    ```

4. Open the project in your chosen IDE and configure the database connection information in the `application.properties` file.

5. Run the Spring Boot application.


## Unit Testing

Unit tests have been implemented using the JUnit framework. To run the tests, use the following command:

```bash
./mvnw test
