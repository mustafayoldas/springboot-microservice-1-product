# Microservice Product

### Endpoints:

#### Save Product

````
POST /api/product HTTP/1.1
Host: localhost:3333
Authorization: Basic base64(username:password)
Content-Type: application/json
Content-Length: 42

{
    "name": "test-1",
    "price": 1.2
}
````

#### Get Products

```
GET /api/product HTTP/1.1
Host: localhost:3333
Authorization: Basic base64(username:password)
```

#### Delete Product

```
DELETE /api/product/{productId} HTTP/1.1
Host: localhost:3333
Authorization: Basic base64(username:password)
```
#   s p r i n g b o o t - m i c r o s e r v i c e - 1 - p r o d u c t  
 