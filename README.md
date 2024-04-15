# MariaDB using docker.

MariaDB port: 3300
phpMyAdmin port: 8000

Docker-compose project creating 1 containers. One container with the MariaDB database.

The docker-compose file contains the container information and can be modified freely. You can change the server's root password and ports.

The main names of the containers are `MariaDB` for MariaDB. As a result, all the scripts took these container names into account.

# Starting the project

Have the docker and docker-compose installed on your machine.

## `Docker_scripts` directory

This directory contains some scripts for managing the containers.

`logs.sh`: Displays the MariaDB container log.

`start.sh`: Start the MariaDB and Adminer containers.

`stop.sh`: Stop containers.

`remove.sh`: Pause and remove containers.

`remove_volumes.sh`: Pause, remove containers and delete all volumes.
