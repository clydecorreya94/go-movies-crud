Build a CRUD API (Web development with golang)

**To run the code**

    # go run main.go

Use Postman or Insomnia or any REST Client

GET ALL (GET): http://localhost:8000/movies
GET BY (GET) : http://localhost:8000/movies/{id}
CREATE (POST) : http://localhost:8000/movies
UPDATE (PUT) : http://localhost:8000/movies/{id}
DELETE (DELETE) : http://localhost:8000/movies/{id}

**To generate executable file**

    # go build 

**To run executable file**
    # ./go-movies-crud

**Issues and debugging**

*Starting server at post 8080*
*listen tcp :8080: bind: address already in use*
*exit status 1*

If the above error return while running the main.go, use the below script

    # sudo kill -9 `sudo lsof -t -i:8080`



