# Basic GO command line

### Write the following syntax to start GO server
```
go run main.go
```

## POST new book method syntax
```
curl localhost:8080/books --include --header "Content-Type: application/json" -d @body.json --request "POST"
```

## Modify book method syntax

### Checkout one book
```
curl localhost:8080/checkout?id= --request "PATCH"
```

### Return one book
```
// curl localhost:8080/return?id= --request "PATCH"
```
