# Knockout-File-Bind
Custom binding to upload files in knockout. 

Two functions: 

Custom binding code that creates a custom binding to be use in knockout. These custom bindings should really only be used for the "file" input type in html. 
These bindings include: 
  1. file: returns the name of a file uploaded
  2. fileBinary: returns an arraybuffer of all the bytes that create the file uploaded
  
The second function is used to convert an arraybuffer into a byte array that can be sent through JSON into a controller to be used. 
