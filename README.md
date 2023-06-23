# envenvenv

## Deployment

To deploy this project, copy .env file matching your target environment

```sh 
# On production
docker compose up -d 
```

## Local development

To develop locally, start the stack with the command below

```sh 
docker compose -f docker-compose.local.yml up -d
```
