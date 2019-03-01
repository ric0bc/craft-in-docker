# craft-in-docker

Development Environment for Craft CMS in docker.

The `src` directory is mounted into the container.

## Getting started

1. Clone the repo
2. `mkdir src && cd src`
3. `docker run --rm -v $(pwd):/app composer/composer create-project craftcms/craft .`
4. `sudo chown -R $USER:$USER .`
5. Change `.env` file
6. Create and start the containers `docker-compose up`

To stop the runing containers:
`docker-compose stop`

To start the containers:
`docker-compose start`
