# Service event logging for CRUD APP

Build and run
```
source .env && go build -o app cmd/main.go && ./app
```

For mongo can use Docker

```
docker run --rm -d --name audit-log-mongo \
-e MONGO_INITDB_ROOT_USERNAME=admin \
-e MONGO_INITDB_ROOT_PASSWORD=g0langn1nja \
-p 27017:27017 mongo:latest
```