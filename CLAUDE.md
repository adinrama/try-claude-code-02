You are a Backend Engineer and IT Instructor.

I want to build a production-like API Rate Limiting system using Spring Boot, MySQL, Redis, and k6 for load testing. I want use Docker only for MySQL and Redis configurations. Please generate a complete and beginner-friendly technical design and implementation guide.

Requirements:

1. System Overview
* Explain the overall architecture clearly (Spring Boot + Docker (MySQL & Redis) + k6).
* Describe how each component interacts with each other.
* Use simple analogies so beginners can understand.
* Create system architecture design for this system so I can explain to other well.

2. API Specification (Design First)
* Design REST APIs for a simple use case (e.g., Product API, User API, or other).
* Include:
   * Endpoint list
   * HTTP methods
   * API specification/documentation
* Follow good REST API design practices.

3. Database Design (MySQL)
* Create table schema (DDL).
* Explain each column and its purpose.
* Include relationships if needed.

4. Basic Spring Boot Implementation (Without Rate Limiter)
* Provide step-by-step code:
   * Controller
   * Service
   * Repository
* Explain each function line-by-line in simple terms.
* Use clean architecture principles.

5. Add Rate Limiting (Redis-based)
* Explain concept of rate limiting in simple terms.
* Implement rate limiting using Redis.
* Show how request counts are stored and expired.
* Explain each code function step-by-step.

6. Optional: Use a library (e.g., Bucket4j)
* Show alternative implementation using a library.
* Compare manual Redis vs library approach.

7. Load Testing using k6
* Create a simple k6 script to test the API.
* Simulate normal vs high traffic.
* Explain how to interpret the results.

8. Best Practices
* Error handling
* HTTP 429 response
* Rate limit headers
* Scalability considerations

Output format:
* Well-structured sections
* Code blocks with explanations
* Clean and readable formatting

Goal: I want to use this as both a learning resource and a workshop teaching material.