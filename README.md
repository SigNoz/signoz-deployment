## To install SigNoz

```
1. git clone https://github.com/SigNoz/signoz-deployment.git && cd signoz-deployment
2. docker-compose up -d
```

`docker ps` should show 6 running containers.
SigNoz UI should be accessible at `http://localhost:3000`


## To Uninstall SigNoz and clean up volumes
```
docker-compose down -v
```