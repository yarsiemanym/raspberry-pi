# Raspberry Pi

TODO

## .env File

```
POSTGRES_DB=...
POSTGRES_USER=...
POSTGRES_PASSWORD=...
DOMAIN_NAME=...
EMAIL_ADDRESS=...
```

## Ports

nextcloud.{domain-name} => Nextcloud
bitwarden.{domain-name} => Bitwarden
blog.{domain-name} => Drupal
pi-hole.{domain-name} => Pi-hole


## Links

- [Raspberry Pi 4](https://www.raspberrypi.org/products/raspberry-pi-4-model-b/)
- [Raspberry Pi OS](https://www.raspberrypi.org/downloads/)
- [Get Started With Docker on Raspberry Pi](https://www.electromaker.io/tutorial/blog/get-started-with-docker-on-the-raspberry-pi)
- [Docker Compose](https://docs.docker.com/compose/)
- [Docker Hub](https://hub.docker.com)
  - [Postgres Container Image](https://hub.docker.com/_/postgres)
  - [Nextcloud Container Image](https://hub.docker.com/_/nextcloud)
  - [Bitwarden Container Image](https://hub.docker.com/r/bitwardenrs/server)
  - [Drupal Container Image](https://hub.docker.com/_/drupal/)
  - [Pi-hole Container Image](https://hub.docker.com/r/pihole/pihole)
  - [Nginx Proxy](https://hub.docker.com/r/jwilder/nginx-proxy)