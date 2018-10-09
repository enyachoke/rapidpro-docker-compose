# rapidpro-docker-compose

A deployable rapidpro docker-compose setup. Batteries included:
- ssl via letsencrypt
- backing services: elasticsearch, postgres, redis, etc.
- celery tasks

To deploy, copy `sample.env` to `.env`, edit it for correct values and then run `docker-compose up`

Note: elasticsearch is currently using ephemeral storage.

Works reasonably well on a single host. Will test on docker swarm cluster next.
