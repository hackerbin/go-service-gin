# Simple Web api application developed in Golang and Gin

## Initial Tutorial URL
`https://go.dev/doc/tutorial/web-service-gin#prerequisites`

## To install dependencies
```
go get .
```

## To run the project
go run .


## Test API
::GET /albums 
```
$ curl http://localhost:8080/albums
```
::GET /albums/:id  
```
$ curl http://localhost:8080/albums/1
```  
::POST /albums 
```
$ curl http://localhost:8080/albums \
    --include \
    --header "Content-Type: application/json" \
    --request "POST" \
    --data '{"id": "4","title": "The Modern Sound of Betty Carter","artist": "Betty Carter","price": 49.99}'
```

## Sample data
```
[
{ID: "1", Title: "Blue Train", Artist: "John Coltrane", Price: 56.99},  
{ID: "2", Title: "Jeru", Artist: "Gerry Mulligan", Price: 17.99},  
{ID: "3", Title: "Sarah Vaughan and Clifford Brown", Artist: "Sarah Vaughan", Price: 39.99},  
]
```
