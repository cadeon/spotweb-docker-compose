# spotweb-docker-compose
Everything you need to run SpotWeb with docker-compose (including a working MySQL backing database instance). Simply type `docker-compose build && docker-compose up -d` after copying over the `.env` file from the `.env.sample` file (with a new set of `DBROOT` and `DBPASS` passwords of course :) ).


# Original SpotWeb image/ Dockerfile/ entrypoint.sh

Originally based on (but modified and OPCache enabled) https://github.com/jgeusebroek/docker-spotweb
