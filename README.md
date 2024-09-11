README: Project Migration Instructions
Overview
This project is developed in Java using the Spring Framework and Java Persistence API
(JPA). To migrate and set up this project on your local machine, follow the steps outlined
below.
Prerequisites
1. Ensure that Java Development Kit (JDK) version 17 is installed on your computer.
Step-by-Step Setup Instructions
2. Install Project Dependencies
• It is highly recommended to use IntelliJ IDEA IDE to manage dependencies
efficiently. IntelliJ IDEA simplifies the dependency management lifecycle,
allowing you to easily install and update dependencies specified in the
pom.xml file.
• Alternatively, if you do not have IntelliJ IDEA, you can install the
dependencies listed in pom.xml using any other method of your choice.

3. Set Up Oracle Database
• Before running the project, you need to set up an Oracle Database using the
configuration provided in the application.properties file. The database
details are as follows:
▪ Database Name: ORCLDB
▪ Database Username: SYS
▪ Database Password: mypassword1
▪ Authentication Type: Default
▪ Role: SYSDBA
▪ Hostname: localhost
▪ Port: 1521
• You may modify the database name, username, password, hostname, and
port as needed. However, ensure that these values match the information
specified in the DataSource connection settings in application.properties.
4. Run the Project
• After setting up the Oracle Database, you can run the project within a
container. The project will be hosted on port 8080 by default.
5. Test and Visualize the API
• Once the project is running, you can test and visualize the API using tools like
Swagger UI or Postman.

By following these steps, you will be able to successfully migrate and run the project on
your local environment. If you encounter any issues or have further questions, please refer
to the project documentation or seek support.
