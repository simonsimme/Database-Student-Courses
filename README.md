Student Portal Database Project
Overview
Welcome to the Student Portal Database Project! This project is designed to manage student information, course registrations, and academic progress within a university setting. The database is built using PostgreSQL and includes various tables, views, and triggers to ensure data integrity and provide comprehensive insights into student performance and course management.

Features
Student Information Management: Store and manage detailed information about students, including their ID, name, login, program, and branch.
Course Management: Handle course details, including course codes, names, credits, and associated departments.
Registration System: Manage student registrations for courses, including handling waiting lists for courses with limited capacity.
Academic Progress Tracking: Track students' completed courses, grades, and credits to determine their eligibility for graduation.
Views and Triggers: Utilize SQL views and triggers to automate data processing and ensure data consistency.
Project Structure
The project is structured into several key components:

ER Model: The project began with the creation of an Entity-Relationship (ER) model to define the database schema. This model outlines the relationships between different entities such as students, courses, and departments.

Tables: Based on the ER model, we created the necessary tables to store data. These tables include constraints to ensure data integrity.
Views: We created SQL views to simplify data retrieval and provide meaningful insights. For example, the BasicInformation view combines student details with their branch information.
Triggers: Triggers were implemented to automate certain actions, such as managing course registrations and updating waiting lists.

Java Application: A software application was developed in Java to interact with the database. This application allows users to register and unregister for courses, and retrieve detailed student information in JSON format.

Learning Outcomes
Throughout this project, I gained valuable experience in:

Database Design: Understanding the principles of database design, including normalization and the creation of ER models.
SQL: Writing complex SQL queries, views, and triggers to manage and manipulate data.
PostgreSQL: Utilizing PostgreSQL as the database management system and leveraging its advanced features.
Java: Developing a Java application to interact with the database using JDBC.
Data Integrity: Ensuring data integrity through the use of constraints, triggers, and proper database design.
Process
The development process followed a structured approach:

ER Model: We started by designing the ER model to define the relationships between different entities.
Tables: Based on the ER model, we created the necessary tables with appropriate constraints.
Views: We then created SQL views to simplify data retrieval and provide meaningful insights.
Triggers: Triggers were implemented to automate certain actions and ensure data consistency.
Java Application: Finally, we developed a Java application to interact with the database and provide a user-friendly interface.
Screenshots
Screenshot 1 Screenshot 2

Conclusion
This project provided a comprehensive understanding of database design and development, from initial modeling to implementation and application development. It showcases the ability to manage complex data relationships and ensure data integrity through the use of advanced SQL features and Java programming.

Thank you for taking the time to review this project! If you have any questions or would like to learn more, please feel free to reach out.

✨ Happy Coding! ✨
