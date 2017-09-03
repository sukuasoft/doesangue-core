[![Packagist](https://img.shields.io/packagist/v/doesangueorg/core.svg)](https://packagist.org/packages/doesangueorg/core)
[![Build Status](https://travis-ci.org/doesangueorg/doesangue-core.svg?branch=master)](https://travis-ci.org/doesangueorg/doesangue-core)
[![Build Status](https://travis-ci.org/doesangueorg/doesangue-core.svg?branch=development)](https://travis-ci.org/doesangueorg/doesangue-core)
[![codecov](https://codecov.io/gh/doesangueorg/doesangue-core/branch/development/graph/badge.svg)](https://codecov.io/gh/doesangueorg/doesangue-core)
[![Scrutinizer Code Quality](https://scrutinizer-ci.com/g/doesangueorg/doesangue-core/badges/quality-score.png?b=development)](https://scrutinizer-ci.com/g/doesangueorg/doesangue-core/?branch=development)
[![Build Status](https://scrutinizer-ci.com/g/doesangueorg/doesangue-core/badges/build.png?b=development)](https://scrutinizer-ci.com/g/doesangueorg/doesangue-core/build-status/development)


#### Topics.
* [What](#what)?
* [Why](#why)?
* [Development](#development)
* [Contributing](#contributing)

![Mente Digital HQ](public/img/logo.jpg)
*Core maintained by Mente Digital Inc and awesome opensource contributors.*


## What?
doesangue.me is a free (and opensource) platform that connects people interesting in blood donation.

## Why?


## Development

### assets

```shell
yarn # install node/js/css dependencies
```
or
```shell
npm install # install node/js/css dependencies
```

### Docker

- Docker 1.12+
- docker-compose 1.8+

```shell
docker-compose run app composer install # install php dependencies
```

```shell
docker-compose run app php artisan key:generate # generate the API_KEY
```

```shell
docker-compose run app php artisan migrate --seed # run the migrations
```

##### Artisan commands
Using the command `docker-compose run app php artisan` you can see all available artisan commands

Ex:

```shell
docker-compose run app php artisan # list the commands
docker-compose run app php artisan route:list # list all routes of our API
```

#### Service
> By default the API run's in `localhost:8080`

```shell
docker-compose up # run's the service
```

To run the service in background:

```shell
docker-compose up -d # run's the service in background
docker-compose down # stop and kill the service
```


### Contributing
To contribute to this repo, please check the documentation/guide at [Contributing](CONTRIBUTING.md)

-----------------
If you prefer to read the portuguese version please check [README PT](README_PT.md) 
