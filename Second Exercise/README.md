# DevOps Challenge

## First time setup

```bash
git clone https://github.com/craftech-inc/devops-challenge
cd devops-challenge

cp .env.sample .env
# Update vars in .env
docker-compose build
```

## Run

```bash
docker-compose up

# Build frontend
docker-compose run --rm ui npm run build
```
