# Web-API-.Net-Core

## Web API

### [ApiController] attribute

This attribute indicates that the controller responds to web API requests.

### Return values

The return type of the GetTodoItems and GetTodoItem methods is ActionResult<T> type. ASP.NET Core automatically serializes the object to JSON and writes the JSON into the body of the response message. The response code for this return type is 200, assuming there are no unhandled exceptions. Unhandled exceptions are translated into 5xx errors.