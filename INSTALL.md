<<<<<<< HEAD
# Installation of fhooe-hypernode-dock
>>>>>>> 5a5d1e46e6436c2ff217f5c080b2291cdcb909c8

## Get repo

Install it in any path on your computer.
Open Powershell (PS) or other Terminal (prompt may be different in this case).

```shell
git clone https://github.com/rru-hgb/fhooe-hypernode-dock.git
```

## Docker

```shell
<<<<<<< HEAD
cd fhooe-hypernode-dock
>>>>>>> 5a5d1e46e6436c2ff217f5c080b2291cdcb909c8
docker compose up -d
```
Access mongodb via commandline in container
```shell
docker exec -it mongo /bin/bash -c "mongosh"
```
Access node container
```shell
docker exec -it hypernode /bin/bash
```
Subfolder node/ is mapped to /home/node in node container. 


### External Ports

Access them via localhost:nnnn
```
22222 MongoDB 
3333 Express
5555 Vite Dev Server
9999 Mongo-Express
```

### Internal Mongo Connection:

mongo:27017
