# Assignment 1

### Objectives
1. Check if the application has connectivity to the database.
    - Return HTTP 200 OK if the connection is successful.
    - Return HTTP 503 Service Unavailable if the connection is unsuccessful.
2. The API response should not be cached. Make sure to add cache-control: 'no-cache' header to the response.
3. The API request should not allow for any payload. The response code should be 400 Bad Request if the request includes any payload.
4. The API response should not include any payload.
5. Only HTTP GET method is supported for the /healthz endpoint.

### Things to Remember
1. The datasource bean represents the database connection given in application.yml file
2. To stop db we can go to services.msc and stop the service (Windows)
3. Add .env file to the intelliJ env variables