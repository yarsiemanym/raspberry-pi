# Raspberry Pi

1. Install Raspberry Pi Imager
2. Flash Raspberry Pi OS to a microSD card using Raspberry Pi Imager
3. Insert microSD card into Raspberry Pi
4. Connect keyboard, mouse, and monitor to Raspberry Pi
5. Turn on Raspberry Pi
6. Follow on-screen setup instructions
7. Clone this repo on Raspberry Pi
8. Install Docker on Raspberry Pi
9. Install Docker Compose on Raspberry Pi
10. 

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