# Microservice architecture for backend
## History
| Date       | Version | Author | Description     |
|------------|-------|--------|-----------------|
| 13/10/2023 | 1.0   | DatDT  | Initial version |
## I. Overview diagram
## 1. Microservices
### 1.1. User service
Manage user information: register, login, authorization, user profile
### 1.2. Content management service
Manage English content: lesson, exam, learning documentation and mark the user's learning progress
### 1.3. Dictionary service
Provide dictionary, translate English to target language (maybe need to integrate with third party if the application don't have)
### 1.4. Machine learning service
Evaluate user level in English and suggest the lesson for user
### 1.5. Analytics and monitoring service
Track user activities, collect statistic data and application performance information
### 1.6. Payment service
Manage payment process
### 1.7. Notification service
Manage user notifications, admin notification and other notifications
### 1.8. Authentication service
Authenticate user and provide token for user
### 1.9. Course management service
If application provide learning courses, this service will manage course information, lesson, learning schedule and learning progress
### 1.10. User Interaction Service
Manage user interaction include: live chat, forum, comments and rating


