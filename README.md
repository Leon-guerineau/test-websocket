# Tasks Organizer

A tool who's primary objective is to help its users to manage their tasks

# Instructions

- ## Start the docker environment

```Shell
docker-compose up -d
```

- ## Install the composer packages

```Shell
docker exec -it test-websocket-php bash -c 'composer install'
```

- ## Launch the websocket server

```Shell
docker exec -it test-websocket-php bash -c 'php cmd.php'
```

- ## Access the PHP container's bash in a terminal
```Shell
docker exec -it test-websocket-php bash
```


