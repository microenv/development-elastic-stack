# Elastic stack (ELK) on Docker Compose

[![Join the chat at https://gitter.im/deviantony/docker-elk](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/deviantony/docker-elk?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
[![Elastic Stack version](https://img.shields.io/badge/ELK-7.6.0-blue.svg?style=flat)](https://github.com/deviantony/docker-elk/issues/473)
[![Build Status](https://api.travis-ci.org/deviantony/docker-elk.svg?branch=master)](https://travis-ci.org/deviantony/docker-elk)

---

### Get Elastic free software running in docker-compose in less than 5 minutes.

---

This repo installs the following software on docker-compose:

* [Elasticsearch](https://github.com/elastic/elasticsearch/tree/master/distribution/docker)
* [Logstash](https://github.com/elastic/logstash/tree/master/docker)
* [Kibana](https://github.com/elastic/kibana/tree/master/src/dev/build/tasks/os_packages/docker_generator)
* [Filebeat](https://github.com/elastic/beats/tree/master/filebeat)

All this softwares are free and opensource, so you don't need to care about paying.

## Development setup

Just run:

```shell
docker-compose up
```

## Uninstall

```shell
docker-compose down -v
```

## Production usage

> Please do not use this in production unless you know what you're doing. This repo was created to setup a local development environment for Elastic free softwares.

## References

- https://github.com/deviantony/docker-elk
- https://github.com/shazChaudhry/docker-elastic
