# Jobs API
check it out [here](https://jobs-api-docs-4s4o.onrender.com)

**Register User**

-   Validate - name, email, password - with Mongoose
-   Hash Password (with bcryptjs)
-   Save User
-   Generate Token
-   Send Response with Token

**Login User**

-   Validate - email, password
-   Find User
-   Compare Passwords
-   generate Token
-   Send Response with Token

    **Mongoose Errors**

-   Validation Errors
-   Duplicate (Email)
-   Cast Error

**Security**

-   helmet
-   cors
-   express-rate-limit
