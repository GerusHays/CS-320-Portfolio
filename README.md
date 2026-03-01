# CS-320-Portfolio
# Software Testing and Contact Service Validation

## Overview
This repository contains my Contact Service implementation and associated JUnit tests, along with my testing analysis and reflections. The purpose of this project was to design service classes and create unit tests that validate functionality, enforce constraints, and ensure the software behaves securely and reliably.

The project focused on applying structured testing practices using JUnit 5 to verify that each service met its requirements, handled invalid input correctly, and prevented unsafe or inconsistent system states.

---

## Ensuring Software Is Functional and Secure

I ensured my software was functional and secure by writing unit tests directly based on the system requirements. Instead of only testing expected behavior, I also tested invalid inputs, edge cases, and constraint violations. This included verifying that IDs could not be null, fields did not exceed maximum length, and invalid data triggered exceptions.

Using JUnit assertions such as:

- `assertEquals`
- `assertNotNull`
- `assertThrows`

allowed me to confirm both correct functionality and proper defensive behavior. This ensured the system would reject invalid input rather than silently failing or allowing corrupted data.

Testing exception handling was especially important because it ensures the system fails safely instead of creating security or data integrity issues.

---

## Interpreting User Needs and Incorporating Them into Software

I interpreted user needs by reviewing the software requirements and translating each requirement into both implementation logic and unit tests. For example, if a requirement stated that a contact ID must not exceed a certain length, I implemented validation in the service class and created test cases to confirm both valid and invalid scenarios.

This approach ensured traceability between requirements, implementation, and testing. It also ensured the system behaves exactly as intended rather than relying on assumptions.

By aligning testing directly with requirements, I ensured the software meets both functional and reliability expectations.

---

## My Approach to Designing Software

My approach to software design follows a structured process:

1. Review and understand system requirements  
2. Design classes and services to meet those requirements  
3. Implement validation and defensive programming  
4. Write unit tests alongside development  
5. Test both valid and invalid inputs  
6. Refactor and improve maintainability  

I use unit testing as a core part of development rather than treating it as a separate step. Writing tests early helps identify problems quickly and prevents defects from propagating through the system.

This approach improves reliability, maintainability, and long-term scalability.

---

## Testing Strategy and Techniques Used

Primary testing techniques used:

**Unit Testing**
- Tested individual service classes in isolation
- Verified logic, validation, and exception handling

**Boundary Testing**
- Tested maximum string lengths
- Tested minimum and invalid values

**Negative Testing**
- Verified system behavior with invalid input
- Confirmed exceptions were thrown when expected

**Requirement-Based Testing**
- Built tests directly from requirement statements
- Ensured full requirement coverage

These techniques ensured both functional correctness and robustness.

---

## Verifying Secure and Reliable Code

I verified security and reliability by:

- Testing invalid and malicious input scenarios
- Confirming exceptions were properly handled
- Ensuring invalid objects could not be created
- Verifying data integrity was maintained
- Running tests after refactoring to ensure nothing broke

This helped confirm that improvements did not introduce new defects or vulnerabilities.

---

## Tools and Technologies Used

- Java
- JUnit 5
- Object-Oriented Programming (OOP)
- Unit Testing Frameworks
- Defensive Programming Techniques

---

## Skills Demonstrated

- Unit testing and test-driven thinking  
- Requirement-based software validation  
- Secure coding practices  
- Exception handling and validation  
- Software quality assurance  
- Writing maintainable and testable code  

---

## Portfolio Purpose

This artifact demonstrates my ability to develop software alongside structured testing and validation. It highlights my ability to ensure software reliability, enforce constraints, and apply professional testing practices to prevent defects and maintain system integrity.
