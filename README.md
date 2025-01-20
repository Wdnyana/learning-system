## Project Overview

# This project is a Learning Management System (LMS) API for educational. This LMS allows:

    - Students to enroll in courses, access materials, and view grades.
    - Instructors to manage course materials, assign tasks, and enter grades.
    - Admins to manage users (instructors, students) and courses.

# This project is designed as a backend API providing RESTful endpoints for connected frontend or mobile applications.

# Technologies Used

    Backend:
        - Java Spring Boot for API development.
        - Additional libraries:
            - Spring Security for authentication and authorization.
            - Spring Data Mongo for database interaction.
            - Spring Validation for input data validation.
            - MapStruct for mapping.

    Database:
        - MongoDB.
        - Redis for caching data such as course lists or user data, speeding up repeated requests.

    Deployment Tools:
        - Docker for containerization.
        - Kubernetes for orchestration.
        - CI/CD: GitHub Actions for automated build and deployment.
