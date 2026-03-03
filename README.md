# MuleSoft-Global-Error-Handler-Production
This project implements a Global Error Handler in Mule 4 using APIKit to centrally manage and standardize all common HTTP and API-related errors.
The error handler captures APIKit exceptions and transforms them into structured JSON responses with appropriate HTTP status codes and messages. This ensures consistent error handling across all API endpoints.


Key Features:

  Centralized Global Error Handling
  
  Handles all major APIKit error types
  
  Standardized JSON error response format
  
  Proper HTTP status code mapping
  
  Improved logging and debugging
  
  Production-ready error management structure

Handled Error Types

The global error handler covers:

Error Type	HTTP Code	Message
APIKIT:BAD_REQUEST	400	Bad Request
APIKIT:UNAUTHORIZED	401	Unauthorized
APIKIT:FORBIDDEN	403	Forbidden
APIKIT:NOT_FOUND	404	Resource Not Found
APIKIT:METHOD_NOT_ALLOWED	405	Method Not Allowed
APIKIT:REQUEST_TIMEOUT	408	Request Timeout
APIKIT:UNSUPPORTED_MEDIA_TYPE	415	Unsupported Media Type
APIKIT:INTERNAL_SERVER_ERROR	500	Internal Server Error
APIKIT:NOT_IMPLEMENTED	501	Not Implemented
APIKIT:BAD_GATEWAY	502	Bad Gateway
APIKIT:SERVICE_UNAVAILABLE	503	Service Unavailable
APIKIT:GATEWAY_TIMEOUT	504	Gateway Timeout
