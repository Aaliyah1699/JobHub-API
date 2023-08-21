# Jobs API

**User Model**

Email Validation Regex

```regex
/^(([^<>()[\]\\.,;:\s@"]+(\.[^<>()[\]\\.,;:\s@"]+)*)|(".+"))@((\[[0-9]{1,3}\.[0-9]{1,3}\.[0-9]{1,3}\.[0-9]{1,3}\])|(([a-zA-Z\-0-9]+\.)+[a-zA-Z]{2,}))$/
```

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
