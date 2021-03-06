# env-stack-php

WIP: this is a experiment project

## Requirements
- docker
- execute docker login command in host machine

## Virtual Hosts
```
127.0.0.1		mail
127.0.0.1		chrome
127.0.0.1		firefox
127.0.0.1		selenium-hub
127.0.0.1		im.stack.local
127.0.0.1		api.stack.local
127.0.0.1		www.stack.local
127.0.0.1		bot.stack.local
```

## After run
- install composer dependencies

## How to use this sample project with PHPStorm
- execute http requests
- execute phpunit tests
- execute codeception tests

## Docker commands with Makefile

```bash
make test ........ Execute tests in docker containers
make mail ........ Send an test email to Mailcatcher Inbox
make install ..... Install composer dependencies
make database .... Create a new database in MariaDB container
make migrate ..... Run Phinx migration command
```

## Automated Test Suites
- PHPUnit
- Codeception

### How to test a feature using BDD, Codeception and PHPStorm
- persona
- action
- value

### Running Units Tests with PHPUnit
```bash
bin/phpunit
```

### Running Api Tests with Codeception
```bash
bin/codecept run
```

### Running Tests with Docker Exec
- see docker exec command in `Makefile:docker-tests`

## How to use PHPStorm with Tasks Servers
- clearly given tasks with user stories


## See acceptance tests with VNC

Use VNC client to connect.

Browser | Port
--------|-------
Chrome  | 5900
Firefox | 5901

