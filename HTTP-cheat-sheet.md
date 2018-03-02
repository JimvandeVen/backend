# HTTP cheat sheet

## Create  
* PUT - Creates the data you are adding, or replaces the data if it allready exists.
* POST - Adds the data, does not replace. You can have duplicates this way.

## Read  
* GET - Request a resource.

## Update  
* PATCH - Update a resource, add some data.

## Delete  
* DELETE - Removes a resource  

## Options  
* OPTIONS - Shows the methods you can use.

## Headers  
* Accept
* Content-Type
* Accept-Encoding 
* Content-Encoding
* Authorization

## Status  
| Category        | Range           | Example  |
| ------------- |:-------------:| -----:|
| Information      | 1·· | 101 Switching Protocols |
| Success      | 2··      |   200 OK, 201 Created|
| Redirect | 3··      |    301 Moved Permanently |
| Client error | 4··      |    400 Bad Request, 404 Not Found |
| Server Error | 5··      |    500 Internal Server Error|

