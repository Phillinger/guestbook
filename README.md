# guestbook
"Symfony 5: The Fast Track"

This repository helps me learning to code with symfony. Buy the book ("Symfony 5: The Fast Track") to support the symfony project!

## Usefull commands
### Local web server
1. `symfony server:ca:install`
1. `symfony server:start -d`

*or:*

`symfony server:start -d --no-tls`

`symfony server:log`

`symfony open:local`

### Maker Bundle
`symfony console make:controller ExampleController`

### Docker Compose
`docker-compose up -d`

`docker-compose ps`

`docker-compose logs`

### Doctrine
`symfony console make:entity Example` // Add an entity *Example* or add new fields to it.

`symfony console make:migration` // Create a migration file to add the changes.

`symfony console doctrine:migrations:migrate` // Execute migration.

`symfony console doctrine:fixtures:load` // load fixtures

### Debugger
`symfony console debug:router`

### misc
`symfony book:check-requirements`
