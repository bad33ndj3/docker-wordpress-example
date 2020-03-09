## docker wordpress example

### env
copy the example file to .env and change the values

    $ cp .env.example .env

### start server
    $ docker-compose up -d

### stop server
    $ docker-compose down

### stop server and remove files/database
    $ docker-compose down --volumes
    
source: `https://docs.docker.com/compose/wordpress/`