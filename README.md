
# Docker and Docker Compose template for Medusa and NextJs

This repository is not an official repository of Medusa.

* To build the images and start the application please try `docker compose up`
* After containers are started execute this code to seed the sample data to the database `docker exec <medusa-container-name> npx medusa seed -f ./data/seed.json`

*Replace `<medusa-container-name>` with the container name of medusa service.*

Medusa website: https://medusajs.com
