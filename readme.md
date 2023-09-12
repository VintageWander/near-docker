# Near Docker
Near development blockchain used for testing and deploying locally, by using just a single [`docker-compose`](./docker-compose.yml) file

# How to run
```bash
docker-compose up -d
```
The process will be VERY long (around > 15 minutes), so please grab a cup of coffee and wait <br>
But mostly depends on internet speed, so if your internet speed is fast then the process will take less time

# Ports
The explorer webpage is at `localhost:8331` and the wallet webpage is at `localhost:8334` <br>
The node address is at `localhost:8332`, and the helper url is at `localhost:8330`

# How does this works?
Simple, this is pretty much just the kurtosis environment packaged in a `docker-compose` stack