Runs a [Chronos](https://github.com/airbnb/chronos) instance.

Available on the Docker Index as [measurence/chronos](https://index.docker.io/u/measurence/chronos/):

    docker pull measurence/chronos

### Versions
* Chronos 2.1.0
* Mesos 0.19.0

### Usage

Starting the container:

    docker run \
        --net=host \
        -p 9090:8080 \
        measurence/chronos:latest \
        [CHRONOS_OPTIONS]

(See Chronos's [documentation](https://github.com/airbnb/chronos/blob/master/README.md) for available arguments)

Once the container is up, visit `http://<host>:8090/` and confirm Chronos is running.
