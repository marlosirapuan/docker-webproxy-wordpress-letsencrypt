# Web Proxy using Docker, Wordpress, Let's Encrypt

Use AFTER setup this: [https://github.com/evertramos/docker-compose-letsencrypt-nginx-proxy-companion](https://github.com/evertramos/docker-compose-letsencrypt-nginx-proxy-companion)

Copy `.env.sample` to `.env`
```
cp .env.sample .env
```

Change info `.env` and save
```
vim .env
```

Config `uploads.ini` and `my.cnf` in `/configs` folder

**NOTE:** `docker-compose.yml` using `webproxy` network!

Run
```
docker-compose -up -d
```