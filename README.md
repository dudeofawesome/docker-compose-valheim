# docker-valheim-server

A Docker Compose setup for a Valheim dedicated server.

### Setup

1. Create a `.env` file

    ```conf
    USER_ID=1000
    GROUP_ID=100

    TIMEZONE=America/Los_Angeles

    VALHEIM_SERVER_NAME=Some Name
    VALHEIM_SERVER_WORLD_NAME=Some Other Name
    VALHEIM_SERVER_PASSWORD=password
    ```

1. `$ docker-compose up -d`
