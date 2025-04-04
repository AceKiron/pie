# Installation
To install Pie, run the following command in an empty folder on a 64-bit Raspberry Pi OS system:

```sh
wget -O - https://raw.githubusercontent.com/AceKiron/pie/main/setup.sh | sudo sh -
```

## Post-install instructions
You may need to modify configuration files (see `./homepage/*.yml` and `./docker-compose.yml` files) to allow viewing the webserver on a different IP address or hostname.