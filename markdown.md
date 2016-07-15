class: center, middle
# docker-compose


---

# Agenda

1. Common problems
2. docker-compose to the rescue
3. docker-compose.yml
4. pitfalls

# Common Problems
## Multi Container apps are a hassle
* build images from Dockerfiles
* pull images from the hub or private registry
* start and stopping of containers

```bash
$ docker pull selenium/hub
Using default tag: latest
latest: Pulling from selenium/hub
dde80f7d7068: Already exists
d61acf11302c: Pull complete
Digest: sha256:fc5015b58e11e880ffde69a44677c78b202269011a0c547553c41654648d0197
Status: Downloaded newer image for selenium/hub:latest
```
---
