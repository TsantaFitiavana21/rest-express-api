# Restfull Express API

## Endpoints:

### POST /auth/register

```javascript
{
   "email": "test@test.com",
   "username": "test",
   "password": "123"
}
```

### POST /auth/login

```javascript
{
   "email": "test@test.com",
   "password": "test
}
```

### PATCH /users/:id

```javascript
{
   "username": "updated name"
}
```

### GET /users

### DELETE /users/:id
