# d4w-net
Simple .NET Core application serving static files. The application can be executed in a container like so:  
`docker-compose up`  
and then navigate to http://docker:5004/hello.html

Changes to hello.html is reflected in the running app as the wwwroot folder is mounted in the container.
