# Backend Developer Assessment

Hello Jane Smith,

## Overview
In this assignment, you will be tasked with designing and implementing a RESTful API using Kotlin. This assessment is designed to evaluate your skills in backend development, API design, and your ability to work with data persistence.

## Functional Requirements
1. **User Management API**: 
   - Implement endpoints for user registration, login, and profile retrieval.
   - Endpoints should include:
     - `POST /api/users/register`
     - `POST /api/users/login`
     - `GET /api/users/{id}`

2. **Data Persistence**:
   - Use an in-memory database (e.g., H2) to store user information.
   - Ensure that user passwords are hashed before storage.

3. **Error Handling**:
   - Implement appropriate error handling for invalid requests and server errors.
   - Return meaningful HTTP status codes and messages.

## Technical Expectations
- Use Kotlin as the primary programming language.
- Follow RESTful principles in your API design.
- Write unit tests for your API endpoints using a testing framework of your choice (e.g., JUnit).
- Ensure your code is clean, well-structured, and follows best practices.

## Deliverables
- A GitHub repository containing:
  - The complete source code for the API.
  - A README file with instructions on how to run the application and any dependencies required.
  - Unit tests for the implemented features.

## Time Estimate
You should allocate approximately 5-7 hours to complete this assignment.

## Submission Instructions
Once you have completed the assignment, please create a pull request to submit your work. Ensure that your code is pushed to a public repository on GitHub.

## Final Note
This assignment will be reviewed and discussed in our upcoming interview. We look forward to seeing your solution and understanding your thought process!