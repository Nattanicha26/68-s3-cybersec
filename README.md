# Cyber Security

## Owner
- 6702041511136
- Nattanicha Intam
- s6702041511136@email.kmutnb.ac.th


## Enviroment
```sh
cp env.simple.env
```

## Running services

#Database
```sh
docker compose -f db.yaml up # monitoring
docker compose -f db.yaml up -d # background
```
#admin
```sh
docker compose -f admin.yaml up # monitoring
docker compose -f admin.yaml up -d # background
```

#app
```sh
docker compose -f app.yaml up # monitoring
docker compose -f app.yaml up -d # background
```
