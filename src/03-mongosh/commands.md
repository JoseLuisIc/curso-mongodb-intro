##Connect to container

```sh
docker-compose exec mongodb bash
```

```sh
docker compose exec mongodb mongosh "mongodb://root:root123@localhost:27017/?authMechanism=DEFAULT&tls=false"
```

## Connect with mongosh
```sh
mongosh "mongodb://root:root123@localhost:27017/?tls=false"
mongosh "mongodb+srv://jcaamalic:KaabCode2023@mongodb.5iprrm9.mongodb.net/"
```

```sh
show dbs
show collections
```

```sh
use("platzi_store")
db.products.find()
```
