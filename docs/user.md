# User API Spec

## Register User

Endpoint : POST /api/users

Request Body:

```json
{
  "name": "Bambang Ahmad",
  "age": 40
}
```

Response Body (Success):
```json
"status": "success",
"data": {
"age": 40,
"id": "bb611fda-8773-4672-80bf-f0743b32e35c",
"name": "Bambang Ahmad"
}
}
```


## Update User

Endpoint : PUT /api/users/:id

Request Body:

```json
{
  "name": "Bambang Ahmad",
  "age": 43
}
```

Response Body (Success):
```json
"status": "success",
"data": {
"age": 43,
"id": "bb611fda-8773-4672-80bf-f0743b32e35c",
"name": "Bambang Ahmad"
}
}
```

## Get User
Endpoint : GET /api/users/:id

Response Body (Success):
```json
"status": "success",
"data": {
"age": 43,
"id": "bb611fda-8773-4672-80bf-f0743b32e35c",
"name": "Bambang Ahmad"
}
}
```

## Delete User

Endpoint : DELETE /api/users/:id

Response Body (Success):
```json
{
"status": "success delete user with id bb611fda-8773-4672-80bf-f0743b32e35c"
}
```



