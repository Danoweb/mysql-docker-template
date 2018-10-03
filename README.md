# mysql-docker-template
A template for spinning up a MySQL instance within docker and utilizing the docker networking and local storage configuration.

# Use
* Make sure you have `docker-compose` installed
* Download/Clone the repo into a new directory
* Run the command `docker-compose up --build`

# Volumes
The Volume binding that is created will be a local folder inside the project folder which will contain all the data that is written to the mysql instance.
