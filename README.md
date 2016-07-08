## Instructions

This repository includes a useful file: `docker-compose.yml`

This file is used by [Docker
Compose](http://docs.docker.com/compose/#overview) which orchestrates Docker
container startup.

Install it using pip (see [here](http://docs.docker.com/compose/install/) for
other ways of installing it)

The 'hyperchannel' and 'sockethub' repositories are expected to be checked out
and ran from sibling directories.

Usage of this is like so:

```
$ mkdir 67p
$ cd 67p

$ git clone https://github.com/67p/hyperchannel
$ git clone https://github.com/sockethub/sockethub && cd sockethub && git checkout experimental_v1_0 && cd ../

$ git clone https://github.com/67p/orchestration
$ cd orchestration
$ docker-compose up
```

Afterwards, you can access hyperchannel at http://localhost:4200/ or sockethub
examples at http://localhost:10550/
