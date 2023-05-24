### Connect to container

```sh
docker compose exec mongodb bash
```

### Connect with mongosh

```sh
mongosh "mongodb://nombreUsuario:contraseña@localhost:27017/?authMechanism=DEFAULT&tls=false"
```
