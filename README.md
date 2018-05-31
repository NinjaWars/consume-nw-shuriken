# App for consuming the published nw-shuriken npm

Just `npm install yarn` and:

    yarn start

## Run test environment docker

* Pull down the docker image `docker build -t nw-shuriken-test .`
* Spin up the container `docker run --rm -it -p 8080:8080 nw-shuriken-test`
* Stop the container `docker stop nw-shuriken-test`