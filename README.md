> ```markdown
> # Sales System - Java Swing & MySQL
> ```

> 
>
> <p align="center">
> <img src="https://img.shields.io/badge/Java-8+-ED8B00?style=for-the-badge&logo=java&logoColor=white" alt="Java 8+"/>
> <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL"/>
> <img src="https://img.shields.io/badge/NetBeans-8.2-1B6AC6?style=for-the-badge&logo=apache-netbeans&logoColor=white" alt="NetBeans 8.2"/>
> </p>

> 
>
> -----

> ## About the Project

> This project is a desktop application for sales management, developed in Java with the Swing graphics library. The system demonstrates fundamental software development concepts, such as creating user interfaces (UI), handling events, and integrating with a relational database (MySQL) via JDBC.

> The project's architecture separates responsibilities into packages, containing the interface classes (view), data access objects (DAO), and model classes (beans), facilitating code maintenance and understanding.

> 
>
> -----

> ## Key Features

>   * **Sales Entry:** Intuitive interface to create a new sales note, selecting a customer and adding multiple products.
>   * **Database Integration:** Dynamic loading of customers and products from the database to populate UI components.
>   * **Item Management:** Addition and deletion of items from the sales "cart" before final persistence.
>   * **Database Business Logic (Triggers):** The calculation of the note's total value is automated via triggers in MySQL, ensuring data consistency directly in the database.

> 
>
> -----

> ## How to Run

> ### 1\. Prerequisites

>   * JDK 8 or higher
>   * MySQL Server (XAMPP, WAMP, etc.)
>   * NetBeans IDE 8.2 or higher

> ### 2\. Database Setup

>   * Start your MySQL server.
>   * Create a new database named `SisVendas`.
>   * Import the SQL script contained in the `SisVendas.sql` file (available in the root of this repository) to create the necessary tables and triggers.

> ### 3\. Project Setup

>   * Open the project in the NetBeans IDE.
>   * Add the MySQL Connector/J driver to the project's libraries.
>   * Check and, if necessary, adjust the database access credentials in the connection class (by default, user='root' and password='').

> ### 4\. Execution

>   * Run the main interface file (`CadastroNota.java`) to start the application.

> 
>
> -----
