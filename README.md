# plesk-wp-rocket-nginx-config

These are additional [Nginx](https://nginx.org) directives to be used for [plesk](https://www.plesk.com/) hosted [WordPress](https://wordpress.org) sites using the cache plugin [WP-Rocket](https://wp-rocket.me). It enables Nginx to serve directly previously cached files without calling WordPress or any PHP. It also adds headers to cache CSS, JS and medias in order to leverage browser's cache by reducing request to your web server.

This config is based on [Rocket-Nginx](https://github.com/SatelliteWP/rocket-nginx) by SatelliteWP.

## Installation

To add domain-specific settings for Nginx web servers:

1. Log into Plesk
2. Go to **Home > Subscriptions > example.com > Websites & Domains > Apache & nginx Settings**
3. Add the directives from `rocket-nginx-directives.conf` in the Additional nginx directives field

## Documentation

* [Rocket-Nginx](https://github.com/SatelliteWP/rocket-nginx)

## License

Released under the MIT License. See the license file for details.
