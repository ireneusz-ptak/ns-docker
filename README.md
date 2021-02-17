# Nightscout server
Docker-compose configuration for setting up the Nightscout server along with MongoDB, Nginx reverse proxy and Let's Encrypt SSL certificate.

## Installation
1. [Install docker-compose](https://docs.docker.com/compose/install/#install-compose).

1. Clone this repository: `git clone https://github.com/ireneusz-ptak/ns-docker.git .`

1. Change the configuration filename: `mv .env.template .env`

1. Set domain name, API secret and/or other setting in .env config file

1. Run the init script:
        `./install-ns.sh`

1. Run the server:
        `docker-compose up -d`

## License
All code in this repository is licensed under the terms of the `MIT License`. For further information please refer to the `LICENSE` file.

## 
Certificate installation thanks to https://github.com/wmnnd/nginx-certbot
