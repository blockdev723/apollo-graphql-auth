# Authentication and Authorization with Apollo Federation

**Installation:**

```bash
npm i && npm run server
```

**Tutorial:**

In this tutorial, I will cover how to:

    - Set up Apollo Gateway and an implementing service with a federated schema to manage access to user account data
    - Sign a JWT for a user when they send a login mutation and then use Express middleware to verify the token when sent with subsequent requests from the authenticated user
    - Add an authorization layer to check user permissions before running resolver functions
