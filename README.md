# key_value_database_server
Runs a server that is accessible on http://localhost:4000/
When the server receives a request on http://localhost:4000/set?somekey=somevalue it should store the passed key and value in memory. When it receives a request on http://localhost:4000/get?key=somekey it should return the value stored at somekey.

TODO: the data to a file. start with simply appending each write to the file, and work on making it more efficient if you have time.
