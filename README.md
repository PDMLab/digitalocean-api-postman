# Postman API Collection and environment for DigitalOcean API v2

## Description
This repository provides an [API Collection](DigitalOcean API.postman_collection.json) as well as an [Postman Environment configuration](DigitalOcean.postman_environment.json) for the DigitalOcean API v2.

## Usage
* Import the `DigitalOcean.postman_environment.json` into Postman first and make sure to set the values of the following environment variables in the Postman settings for the `DigitalOcean` environment:
  - `bearer`
  - `region`
* Import the `DigitalOcean API.postman_collection.json`, select the `DigitalOcean` environment and have fun with the DigitalOcean API.

## Supported Requests
* [Account](https://developers.digitalocean.com/documentation/v2/#account)
* [Block Storage](https://developers.digitalocean.com/documentation/v2/#block-storage)

## Todo
Add support for these Requests:
* [Actions](https://developers.digitalocean.com/documentation/v2/#actions) ([#1](https://github.com/PDMLab/digitalocean-api-postman/issues/1))
* [Certificates](https://developers.digitalocean.com/documentation/v2/#certificates) ([#3](https://github.com/PDMLab/digitalocean-api-postman/issues/3))
* [Domains](https://developers.digitalocean.com/documentation/v2/#domains) ([#4](https://github.com/PDMLab/digitalocean-api-postman/issues/4))
* [Domain Records](https://developers.digitalocean.com/documentation/v2/#domain-records) ([#5](https://github.com/PDMLab/digitalocean-api-postman/issues/5))
* [Droplets](https://developers.digitalocean.com/documentation/v2/#droplets) ([#6](https://github.com/PDMLab/digitalocean-api-postman/issues/6))
* [Droplet Actions](https://developers.digitalocean.com/documentation/v2/#droplet-actions) ([#7](https://github.com/PDMLab/digitalocean-api-postman/issues/7))
* [Floating IPs](https://developers.digitalocean.com/documentation/v2/#floating-ips) ([#8](https://github.com/PDMLab/digitalocean-api-postman/issues/8))
* [Floating IP Actions](https://developers.digitalocean.com/documentation/v2/#floating-ip-actions) ([#9](https://github.com/PDMLab/digitalocean-api-postman/issues/9))
* [Firewalls](https://developers.digitalocean.com/documentation/v2/#firewalls) ([#10](https://github.com/PDMLab/digitalocean-api-postman/issues/10))
* [Images](https://developers.digitalocean.com/documentation/v2/#images) ([#11](https://github.com/PDMLab/digitalocean-api-postman/issues/11))
* [Image Actions](https://developers.digitalocean.com/documentation/v2/#image-actions) ([#12](https://github.com/PDMLab/digitalocean-api-postman/issues/12))
* [Load Balancers](https://developers.digitalocean.com/documentation/v2/#load-balancers) ([#13](https://github.com/PDMLab/digitalocean-api-postman/issues/13))
* [Regions](https://developers.digitalocean.com/documentation/v2/#regions) ([#14](https://github.com/PDMLab/digitalocean-api-postman/issues/14))
* [Sizes](https://developers.digitalocean.com/documentation/v2/#sizes) ([#15](https://github.com/PDMLab/digitalocean-api-postman/issues/15))
* [Snapshots](https://developers.digitalocean.com/documentation/v2/#snapshots) ([#16](https://github.com/PDMLab/digitalocean-api-postman/issues/16))
* [SSH-Keys](https://developers.digitalocean.com/documentation/v2/#ssh-keys) ([#17](https://github.com/PDMLab/digitalocean-api-postman/issues/17))
* [Tags](https://developers.digitalocean.com/documentation/v2/#tags) ([#18](https://github.com/PDMLab/digitalocean-api-postman/issues/18))

## Contributions
If you want to contribute, please raise your hands about which part of the DigitalOcean API you would like to add to the collection in one of the [issues](https://github.com/PDMLab/digitalocean-api-postman/issues) or create a new Issue before sending a Pull Request.
