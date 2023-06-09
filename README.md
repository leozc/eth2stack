# eth2stack
a docker stack that runs eth2

## how to run?
Prepare your jwt token
```bash
mkdir -p /home/$USER/.eth2docker/jwtsecret
openssl rand -hex 32 | tr -d "\n" | tee >/home/$USER/.eth2docker/jwtsecret/jwt.hex
```

To run
```bash
docker compose up
```
