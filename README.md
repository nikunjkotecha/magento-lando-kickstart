# Lando based Magento2 local setup

## Introduction

This repo contains Lando based local setup for Magento 2.4 and above.

I've project with Magento EE and all the tools described below are used. 
I need a setup with everything available together.

It has:
* LEMP
* RabbitMQ
* Elasticsearch
* Redis
* PHPMyAdmin
* Mailhog
* XDEBUG enabled by default
* Composer 1 latest configured by default

## Requirements

* [Lando](https://lando.dev/download/)
* Magento code :)

## Usage

* Copy the .lando.yml and .lando directory into your project root
* Do lando start

## Tooling
* `vim` is enabled in for the web server
* We can run magento commands using `lando magento`

## Credits

This was built using following as references
* https://github.com/Tim-MultiSafepay/Lando-RabbitMQ
* https://github.com/improper/lando-magento2-template
