# Cache-Service

## Part2 
### Libraries to Install:
* Run command prompt and navigate to the folder 
* Run the following commands
* go get github.com/gin-gonic/gin
* go get google.golang.org/grpc
* go get google.golang.org/grpc/reflection


### Running the Server and Client:
* cd client
* go run main.go
* Open another Terminal
* cd Server
* go run main.go

### Testing: 
* Go to  `localhost:8080/user/<name>`
* We will recieve desired output 

## Part3
### Prerequisites to Install:
* go get github.com/gin-gonic/gin
* go get github.com/go-redis/redis
* go mod init gitlab.com/idoko/rediboard
* Download and Install Docker  using the command: docker run --name my-redis -p 6379:6379 -d redis

### Running the Part:
* go run main.go

### Testing the Part:
* To set the value of Key-pair and use it such as Ajinkya:Key, Run the following,` localhost:8080/Setuser/<key>/<value>`
* To get the value from the Key-Value pair, Run the following, `localhost:8080/Getuser/<some_name>`

## Part4

### Prerequisites to Install:
* go get github.com/gin-gonic/gin
* go get github.com/go-redis/redis
* go mod init gitlab.com/idoko/rediboard
* Download and Install Docker  using the command: docker run --name my-redis -p 6379:6379 -d redis

### Running the Part:
* go run main.go

### Testing the Part
* To Set the value, Use the following command in local host `localhost:8080/Setuser/<name>/<class>/<roll>`
* To Get the Value, Use `localhost:8080/Getuser/<name>`

