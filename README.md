# NGINX Server

## Building Container From Image

```sh
docker build . --no-cache -t laravel-nginx
```

## Running Container

```sh
docker run -d -p 80:80 -v $(pwd)/src:/var/www/html/public laravel-nginx
```

## Running with Docker Compose

```sh
docker compose up
```
