# NGINX Proxy Setup

Create network:

`docker network create nginx-proxy`

Run another containers with `VIRTUAL_HOST` environment variable and (optionally) with `VIRTUAL_PORT` variable (if service exposing port different form `80`).

Also use `LETSENCRYPT_HOST` and `LETSENCRYPT_EMAIL` variable if using https with *Let's Encrypt* certs.