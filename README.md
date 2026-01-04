## DATABASE MONGODB EN DOCKER:

```
docker run -d -p 27018:27017 -e MONGO_INITDB_ROOT_USERNAME=root -e MONGO_INITDB_ROOT_PASSWORD=root --name mongodb_mentora mongodb/mongodb-community-server:latest
```
