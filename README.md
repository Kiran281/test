DOCUMENTATION:
Endpoint: /api/users

- Method: GET
- Description: Retrieve a list of users with optional filtering by username.
- Parameters:
  - username (optional): Filter users by username.
- Response:
  - 200 OK: Successful request. Returns a list of user objects.
  - 400 Bad Request: Invalid parameters.
  - 401 Unauthorized: Authentication failure.
