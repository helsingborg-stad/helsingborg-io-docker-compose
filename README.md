# labs-docker-compose
A lot of the components used by helsingborg-stad are dockerized; that is, they can be build and ran with [docker](https://www.docker.com/). As such, for ease of development, we use [docker-compose](https://docs.docker.com/compose/) to orchestrate the components locally. For this, we maintain a docker-compose file; thus the existence of this repository.

## Usage

This compose file assumes the following file-structure:

```
  - labs-docker-compose/
    - docker-compose.yml

  - labs-node-js-boilerplate/
    - Dockerfile
```

1. Clone this repository
2. Modify the docker-compose if needed (to suit your specific needs)
3. docker-compose up --build --force-recreate

And that's it!