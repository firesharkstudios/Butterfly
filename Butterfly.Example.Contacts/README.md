# Contact Manager Example

> A simple contact manager app using Vue.js

# Get the Code

```
git clone https://github.com/firesharkstudios/butterfly-server
```

# Run the Server

To run in *Visual Studio*...
- Open *Butterfly.Server.sln*
- Run *Butterfly.Example.Contacts*.

To run in a terminal or command prompt...
```
cd butterfly-server\Butterfly.Example.Contacts
dotnet run
```

You can see the server code that runs at [Program.cs](https://github.com/firesharkstudios/butterfly-server/blob/master/Butterfly.Example.Contacts/Program.cs).

## Run the Client

This assumes you have the [demo server](#run-the-server) running.

```
cd butterfly-server\Butterfly.Example.Contacts\www
npm install
npm run serve
```

Open as many browser instances to http://localhost:8080/ as you wish to confirm the todo list stays synchronized across all connected clients.

**Note:** The server process is listening for API requests on port 8000 and the node dev server is listening on port 8080 and proxying API requests to port 8000.