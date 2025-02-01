This lab builds upon lab2 by introducing API versioning, error handling, and API key authentication using environment variables

Features:
---API Versioning:
apiv1 - initial implementation of t5ask management endponts
apiv2 - enhanced version with http exceptions and API key security
---Error Handling (HTTP Exceptions)
404 Not Found - when accessing, deleting or updating a non-existent task
204 No Content - when no tasks are available
201 Created - when a task is successfully added
204 No content - when a task is successfully updated or deleted
200 OK - for other responses
---API Key Authentication:
uses an .env file to stor3e the API key securely
the API key must be included in requeest headers for access.
.gitignore prevents commiting .env to the repository
