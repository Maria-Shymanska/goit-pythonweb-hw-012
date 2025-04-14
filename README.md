# 1. Code Documentation
All major functions and class methods must include appropriate docstrings to enable documentation generation with Sphinx.

# 2. Testing
Test modules should be organized according to the structure of your application.
Use pytest to write unit and integration tests.
Ensure at least 75% test coverage of your application code. Use pytest-cov to check the coverage.

# 3. Caching with Redis
Set up Redis as a caching service for your application.
When implementing user caching, ensure data security and consistency.

# 4. Password Reset
Implement a secure password reset mechanism with email confirmation or another method.

# 5. Role Management
Implement a role-based system for users.
Ensure access rights are checked when performing operations available to administrators only.

# 6. Storing Sensitive Data
All sensitive data and settings must be stored in a .env file.
Do not include sensitive data in the codebase.

# 7. Containerization
Use Docker Compose to run all services and databases of your application.

Additional Requirements (for extra tasks)

1. JWT Tokens
Implement a secure mechanism for refreshing access tokens using a refresh_token.

2. Cloud Deployment
Ensure your application works correctly after deployment to a selected cloud service.
Submit a link to the working application.
