# envenvenv

## Deployment

To deploy this project, copy .env file matching your target environment

```sh 
# On production
cp .env.prod .env
docker compose up -d 

# On staging
cp .env.staging .env
docker compose up -d 
```

## Local development

To develop locally, start the stack with the command below

```sh 
docker compose -f docker-compose.local.yml up -d
```
