# Docker PHP Project
Docker setup for PHP project workspace

## How to use
- Copy all content in file .env-sample to new file and rename it to .env file
- Change PHP version that suitable for your project
- Change port that you want to use for your project 
- Run terminal and execute
```
docker compose up -d
```

## How to add another PHP version
- Create folder php{{version}} in bin folder
- Create new Dockerfile and customize it

