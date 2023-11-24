# Bookstore

Welcome to the Bookstore Management System! This project allows you to manage a bookstore by adding, updating, and deleting books.

![alt text](https://github.com/EricRaw512/image/blob/main/bookstore.png?raw=true)

## Getting Started

1. **Clone the Repository:**

```bash
git clone https://github.com/your-username/bookstore.git
cd bookstore
```

2. **Create MySQL database**

```bash
create database appointment_planner
```

2. **Configure JDBC Connection:**

- Open the `webapp/WEB-INF` file in your preferred text editor.

- Locate the JDBC connection parameters (URL, username, password) in the following section:

    ```java
    String jdbcUrl = "jdbc:mysql://localhost:3306/bookstore";
    String username = "your-username";
    String password = "your-password";
    ```
- If you are not using MySQL, replace the MySQL JDBC driver in `BookDAO` file.

3. **Run maven clean install:**

```bash
mvn clean install
```

4. **Run the Server using Tomcat Server**

- Run the `bookstore.war` file using tomcat
