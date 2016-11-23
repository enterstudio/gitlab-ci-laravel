# GitLab CI runner for PHP including Git, Composer and PHPUnit

Docker images for GitLab CI runner built on top of the [official PHP images](https://hub.docker.com/r/_/php/) with the addition of some common and useful extensions for Laravel Framework.

## Available tags and `Dockerfile` links
- [`latest` (_Dockerfile_)](https://github.com/Rias500/gitlab-ci-laravel/blob/master/7.0/Dockerfile)
- [`7.0` (_7.0/Dockerfile_)](https://github.com/Rias500/gitlab-ci-laravel/blob/master/7.0/Dockerfile)

## Installed extensions
The following modules and extensions have been enabled,
in addition to those you can already find in the [official PHP image](https://hub.docker.com/r/_/php/):

- `mcrypt`
- `mbstring`
- `curl`
- `json`
- `pdo_mysql`
- `exif`
- `tidy`
- `zip`
- `gd`
- `ldap`

## Composer
[Composer](https://getcomposer.org) is installed globally in the all images.

## PHPUnit & CodeSniffer
[PHPUnit](https://phpunit.de/) and [CodeSniffer](https://github.com/squizlabs/PHP_CodeSniffer) are installed globally in the all images.