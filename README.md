# Docker and Docker Compose template for Medusa and NextJs

To build the images and start the application please try

`docker compose up`

After containers are started execute this code to seed the sample data to the database

`docker exec <medusa-container-name> npx medusa seed -f ./data/seed.json`

* replace <medusa-container-name> with the container name of medusa service.