# youpi matin ☕️

## Deployment

To test the staging and production environments : 

```sh 
# Run production environment
docker compose -f docker-compose.demo.prod.yml up -d 

# Run staging environment
docker compose -f docker-compose.demo.staging.yml up -d 
```

## Local development

To develop locally :

```sh 
docker compose up -d
```
