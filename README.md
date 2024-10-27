# esprit-cheatsheat
 
# 3A

## Symfony

install symfony

```sh
composer create-project symfony/skeleton:6.4.* Template
composer require webapp
symfony server:start 
symfony serve
```

make controller

```sh
symfony console make:controller
```

setup database

change .env file:
`DATABASE_URL="mysql://root:@127.0.0.1:3306/DB_name"`

```sh
Symfony console doctrine:database:create
```

make entity

```sh
symfony console make:entity
```

migration

```sh
symfony console make:migration
symfony console doctrine:migrations:migrate
```