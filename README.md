# mysql-docker-template
A template for spinning up a MySQL instance within docker and utilizing the docker networking and local storage configuration.

# Use
* Make sure you have `docker-compose` installed
* Download/Clone the repo into a new directory
* Run the command `docker-compose up --build`

# Volumes
The Volume binding that is created will be a local folder inside the project folder which will contain all the data that is written to the mysql instance.

# Networking
The container is setup to join a docker network called `datanet`.  Any other containers which join this docker network can refer to this container (and access the mysql instance running within it) by using the hostname: `data-mysql` and port `3306`
