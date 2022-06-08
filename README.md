# docker-lamp

Docker with Apache, MySQL 8.0, PHPMyAdmin and PHP.

I use docker-compose as an orchestrator. To run these containers:

```
docker-compose up -d
```

Open Adminer at [http://127.0.0.1:8080](http://127.0.0.1:8080)

Clone YourProject on `www/` and then, open web [http://127.0.0.1/YourProject](http://127.0.0.1/YourProject)

Run MySQL client:

- `docker-compose exec db mysql -u root -p` 
